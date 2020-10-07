---
title: "task: delta"
description: "Get a set of task resources that have been added, deleted, or updated in a specified taskList."
localization_priority: Normal
author: "avijityadav"
ms.prod: "outlook"
doc_type: apiPageType
---

# task: delta

Namespace: microsoft.graph.todo

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a set of [task](../resources/todo-task.md) resources that have been added, deleted, or updated in a specified [taskList](../resources/todo-tasklist.md).

A **delta** function call for **task** resources in a **taskList** is similar to a GET request, except that by appropriately applying [state tokens](/graph/delta-query-overview) in one or more of these calls, you can query for incremental changes in the **task** in that **taskList**. This allows you to maintain and synchronize a local store of a user's **task** resources without having to fetch the entire set from the server every time.  

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type      | Permissions (from least to most privileged)              |
|:--------------------|:---------------------------------------------------------|
|Delegated (work or school account) | Tasks.ReadWrite    |
|Delegated (personal Microsoft account) | Tasks.ReadWrite    |
|Application | Not supported |

## HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /me/todo/lists/{id}/tasks/delta
GET /users/{id|userPrincipalName}/todo/lists/{taskListId}/tasks/delta
```

## Query parameters

Tracking changes in a **task** collection incurs a round of one or more **delta** function calls. If you use any query parameter 
(other than `$deltatoken` and `$skiptoken`), you must specify 
it in the initial **delta** request. Microsoft Graph automatically encodes any specified parameters 
into the token portion of the `nextLink` or `deltaLink` URL provided in the response. 
You only need to specify any desired query parameters once upfront. 
In subsequent requests, simply copy and apply the `nextLink` or `deltaLink` URL from the previous response, as that URL already 
includes the encoded, desired parameters.

| Query parameter	   | Type	|Description|
|:---------------|:--------|:----------|
| $deltatoken | string | A [state token](/graph/delta-query-overview) returned in the `deltaLink` URL of the previous **delta** function call for the same task collection, indicating the completion of that round of change tracking. Save and apply the entire `deltaLink` URL including this token in the first request of the next round of change tracking for that collection.|
| $skiptoken | string | A [state token](/graph/delta-query-overview) returned in the `nextLink` URL of the previous **delta** function call, indicating there are further changes to be tracked in the same task collection. |

### OData query parameters

- You can use a `$select` query parameter as in any GET request to specify only the properties your need for best performance. The 
**id** property is always returned. 
- Delta query supports `$select`, `$top`, and `$expand` for **task**. 
- There is limited support for `$filter` and `$orderby`:
  * The only supported `$filter` expressions are `$filter=receivedDateTime+ge+{value}` 
  or `$filter=receivedDateTime+gt+{value}`.
  * The only supported `$orderby` expression is `$orderby=receivedDateTime+desc`. If you do not include
  an `$orderby` expression, the return order is not guaranteed. 
- The `$search` query parameter is not supported.

## Request headers
| Name       | Type | Description |
|:---------------|:----------|:----------|
| Authorization  | string  | Bearer {token}. Required. |
| Content-Type  | string  | application/json. Required. |
| Prefer | string  | odata.maxpagesize={x}. Optional. |

## Response

If successful, this method returns a `200 OK` response code and [task](../resources/todo-task.md) collection object in the response body.

## Example
### Request
The following example shows how to make a single **delta** function call, and limit the maximum number of **task** 
in the response body to 2.

To track changes in the **task** resources in a **taskList**, you would make one or more **delta** function calls to get the set
of incremental changes since the last delta query. 
 

### HTTP Request
<!-- { "blockType": "ignored" } -->
``` http
GET https://graph.microsoft.com/beta/me/todo/lists/gDbc8U7HGwADDZocJgAAAA==/tasks/delta?$deltatoken=w0vf2jHg2mBXU-I2AK0FSWl0dopNtG8u5YoM
Prefer: odata.maxpagesize=2
```


### Response
If the request is successful, the response would include a state token, which is either a _skipToken_  
(in an _@odata.nextLink_ response header) or a _deltaToken_ (in an _@odata.deltaLink_ response header). 
Respectively, they indicate whether you should continue with the round or you have completed 
getting all the changes for that round.

The following response shows a _skipToken_ in an _@odata.nextLink_ response header.

>**Note:** The response object shown here might be shortened for readability.

```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 337

{
  "@odata.deltaLink":"https://graph.microsoft.com/beta/me/todo/lists/gDbc8U7HGwADDZocJgAAAA==/tasks/delta?$deltatoken=MoVMZ_DzHG4AhT3WE8VioVS1IXZJ-ArqK5fknOjnKFY",
  "value": [
         "@odata.etag":"W/\"4rfRVIPi9EqXgDbc8U7HGwADLLQ9xQ==\"",
         "importance":"normal",
         "isReminderOn":false,
         "status":"notStarted",
         "title":"empty task3",
         "createdDateTime":"2020-08-12T04:54:29.1925206Z",
         "lastModifiedDateTime":"2020-08-12T04:54:29.4903939Z",
         "id":"AAMkADMwNTcyZjQzLTdkMGItNDdjMy04ZTYwLTJhYmUzNGI5ZDEwMwBGAAAAAAB5M0K0qlJySLOAgV22zPnuBwDit9FUg_L0SpeANtzxTscbAAMNmhwmAADit9FUg_L0SpeANtzxTscbAAMxlnrYAAA=",
         "body":{
            "content":"",
            "contentType":"text"
         }
      },
  ]
}
```

## See also

- [Microsoft Graph delta query](/graph/delta-query-overview)

