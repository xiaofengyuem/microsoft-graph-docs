---
title: "channelIdentity resource type"
description: "Represents a channel in a chatMessage"
author: "RamjotSingh"
localization_priority: Priority
ms.prod: "microsoft-teams"
doc_type: apiPageType
---

# channelIdentity resource type

Namespace: microsoft.graph

**Represents a channel in a chatMessage**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|channelId|String|Id of the channel|
|teamId|String|Id of the team|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.channelIdentity"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.channelIdentity",
  "teamId": "String",
  "channelId": "String"
}
```

