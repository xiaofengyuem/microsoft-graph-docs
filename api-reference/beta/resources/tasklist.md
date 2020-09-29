---
title: "taskList resource type"
description: "A list in Microsoft To Do that contains one or more task resources."
author: "avijityadav"
localization_priority: Normal
ms.prod: "outlook"
doc_type: resourcePageType
---

# taskList resource type

Namespace: microsoft.graph.todo

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

A list in Microsoft To Do that contains one or more [task](./task.md) resources. 

In To Do, there are built-in task lists such as **Flagged emails** and **Tasks** which cannot be renamed or deleted.  You can, however, create additional task lists.

This resource supports
* Adding your data to custom properties as [open extensions](/graph/extensibility-overview)
* Using [delta query](/graph/delta-query-overview) to track incremental additions, deletions and updates.

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List lists](../api/todoApp-list-lists.md) | [taskList](tasklist.md) collection | Get all the [taskList](tasklist.md) in the user's mailbox. |
|[Create taskList](../api/todoApp-post-lists.md) | [taskList](tasklist.md) | Create a [taskList](tasklist.md) in the user's mailbox. |
|[Get task list](../api/tasklist-get.md)|[taskList](tasklist.md)|Read the properties and relationships of the specified [taskList](tasklist.md).|
|[Update task list](../api/tasklist-update.md)|[taskList](tasklist.md)| Update the writable properties of the specified [taskList](tasklist.md).|
|[Delete task list](../api/tasklist-delete.md)|None| Delete the specified [taskList](tasklist.md) .|
|[List tasks](../api/tasklist-list-tasks.md)|[task](task.md) collection|Get all the [task](task.md) resources in the specified list.|
|[Create task](../api/tasklist-post-tasks.md)|[task](task.md)| Create a [task](task.md) in the specified task list.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the task list.|
|id|String| The identifier of the task list, unique in the user's mailbox. Read-only. Inherited from [entity](entity.md)|
|isOwner|Boolean| True if the user is owner of the given task list.|
|isShared|Boolean| True if the task list is shared with other users|
|wellknownListName|wellknownListName| Property indicating the well-known list name if the given list is a well-known list. Possible values are: `none`, `defaultList`, `flaggedEmails`, `unknownFutureValue`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|extensions|[extension](extension.md) collection| The collection of open extensions defined for the task list. Nullable.|
|tasks|[task](task.md) collection|The tasks in this task list. Read-only. Nullable.|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.todo.taskList",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.todo.taskList",
  "id": "String (identifier)",
  "displayName": "String",
  "isOwner": "Boolean",
  "isShared": "Boolean",
  "wellknownListName": "String"
}
```



