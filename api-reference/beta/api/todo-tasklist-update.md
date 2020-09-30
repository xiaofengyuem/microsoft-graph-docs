---
title: "Update taskList"
description: "Update the properties of a taskList object."
author: "avijityadav"
localization_priority: Normal
ms.prod: "outlook"
doc_type: apiPageType
---

# Update taskList
Namespace: microsoft.graph.todo
[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [taskList](../resources/todo-tasklist.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|Tasks.ReadWrite|
|Delegated (personal Microsoft account)|Tasks.ReadWrite|
|Application|Not supported|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /me/todo/lists/{taskListId}
PATCH /users/{id|userPrincipalName}/todo/lists/{taskListId}/tasks
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [taskList](../resources/todo-tasklist.md) object.

The following table shows the properties that are required when you create the [taskList](../resources/todo-tasklist.md).

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Field indicating updated title of the task list.|



## Response

If successful, this method returns a `200 OK` response code and an updated [taskList](../resources/todo-tasklist.md) object in the response body.

## Examples

### Request

# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "sampleKeys": ["AAMkADIyAAAhrbPWAAA="],
  "name": "update_taskList"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/me/todo/lists/AAMkADIyAAAhrbPWAAA=
Content-Type: application/json
Content-length: 167

{
  "displayName": "Vacation Plan"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
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
  "@odata.type": "#microsoft.graph.todo.taskList",
  "id": "AAMkADIyAAAhrbPWAAA=",
  "displayName": "Vacation Plan",
  "isOwner": true,
  "isShared": false,
  "wellknownListName": "none"
}
```



