---
title: "initiator resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# initiator resource type

Namespace: microsoft.graph



**TODO: Add Description**


Inherits from [identity](../resources/identity.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Inherited from [identity](../resources/identity.md)|
|id|String|**TODO: Add Description** Inherited from [identity](../resources/identity.md)|
|initiatorType|initiatorType|**TODO: Add Description**. Possible values are: `user`, `application`, `system`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.initiator"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.initiator",
  "id": "String (identifier)",
  "displayName": "String",
  "initiatorType": "String"
}
```

