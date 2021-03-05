---
title: "presenceSession resource type"
description: "Contains information about a user's presence session."
author: "elvinyang-msft"
localization_priority: Normal
ms.prod: "cloud-communications"
doc_type: resourcePageType
---

# chatInfo resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Contains information about a user's presence session.

## Properties

| Property     | Type              | Description                                            |
| :----------- | :---------------- | :----------------------------------------------------- |
| availability | string | The base presence information.              |
| activity     | string | The supplemental information to availability. |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.presenceSession"
}-->
```json
{
  "availability": "String",
  "activity": "String",
}
```

<!-- uuid: 1ac10d37-91d0-4ad4-a5d5-4e734bf3cf49
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "presenceSession resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->


