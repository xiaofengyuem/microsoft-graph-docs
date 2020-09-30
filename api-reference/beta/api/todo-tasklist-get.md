---
title: "Get taskList"
description: "Read the properties and relationships of a taskList object."
author: "avijityadav"
localization_priority: Normal
ms.prod: "outlook"
doc_type: apiPageType
---

# Get taskList
Namespace: microsoft.graph.todo
[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of a [taskList](../resources/todo-tasklist.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|Tasks.ReadWrite|
|Delegated (personal Microsoft account)|Tasks.ReadWrite|
|Application|Not supported.|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /me/todo/lists/{taskListId}
GET /users/{id|userPrincipalName}/todo/lists/{taskListId}
```

## Optional query parameters
This method supports the [OData query parameters](/graph/query-parameters) to help customize the response.

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [taskList](../resources/todo-tasklist.md) object in the response body.

## Examples

### Request

# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "sampleKeys": ["AAMkADIyAAAAABrJAAA="],
  "name": "get_todo.tasklist"
}
-->
``` http
GET https://graph.microsoft.com/beta/me/todo/lists/AAMkADIyAAAAABrJAAA=
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.todo.taskList"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.todo.taskList",
    "id": "5daae1ed-e1ed-5daa-ede1-aa5dede1aa5d",
    "displayName": "Monthly tasks",
    "isOwner": "true",
    "isShared": "false",
    "wellknownListName": "defaultList"
  }
}
```



