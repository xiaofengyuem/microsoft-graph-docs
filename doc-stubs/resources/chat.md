---
title: "chat resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# chat resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List chats](../api/user-list-chats.md)|[chat](../resources/chat.md) collection|Get the chat resources from the chats navigation property.|
|[Create chats](../api/user-post-chats.md)|[chat](../resources/chat.md)|Create a new chat object.|
|[Update chats](../api/user-update-chats.md)|[chat](../resources/chat.md)|Update the properties of a chats object.|
|[Get chats](../api/user-get-chat.md)|[chat](../resources/chat.md)|Read the properties and relationships of a [chat](../resources/chat.md) object.|
|[Delete chats](../api/user-delete-chats.md)|None|Delete a [chat](../resources/chat.md) object.|
|[List chats](../api/chat-list.md)|[chat](../resources/chat.md) collection|Get a list of the [chat](../resources/chat.md) objects and their properties.|
|[Create chat](../api/chat-post-chats.md)|[chat](../resources/chat.md)|Create a new [chat](../resources/chat.md) object.|
|[Get chat](../api/chat-get.md)|[chat](../resources/chat.md)|Read the properties and relationships of a [chat](../resources/chat.md) object.|
|[Update chat](../api/chat-update.md)|[chat](../resources/chat.md)|Update the properties of a [chat](../resources/chat.md) object.|
|[Delete chat](../api/chat-delete.md)|None|Deletes a [chat](../resources/chat.md) object.|
|[List tabs](../api/chat-list-tabs.md)|[teamsTab](../resources/teamstab.md) collection|Get the teamsTab resources from the tabs navigation property.|
|[Create tabs](../api/chat-post-tabs.md)|[teamsTab](../resources/teamstab.md)|Create a new teamsTab object.|
|[Get tabs](../api/chat-get-teamstab.md)|[teamsTab](../resources/teamstab.md)|Read the properties and relationships of a [teamsTab](../resources/teamstab.md) object.|
|[Update tabs](../api/chat-update-tabs.md)|[teamsTab](../resources/teamstab.md)|Update the properties of a tabs object.|
|[Delete tabs](../api/chat-delete-tabs.md)|None|Delete a [teamsTab](../resources/teamstab.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|
|topic|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|installedApps|[teamsAppInstallation](../resources/teamsappinstallation.md) collection|**TODO: Add Description**|
|members|[conversationMember](../resources/conversationmember.md) collection|**TODO: Add Description**|
|messages|[chatMessage](../resources/chatmessage.md) collection|**TODO: Add Description**|
|tabs|[teamsTab](../resources/teamstab.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.chat",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.chat",
  "id": "String (identifier)",
  "topic": "String",
  "createdDateTime": "String (timestamp)",
  "lastUpdatedDateTime": "String (timestamp)"
}
```

