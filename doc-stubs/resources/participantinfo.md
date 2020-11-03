---
title: "participantInfo resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# participantInfo resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|countryCode|String|**TODO: Add Description**|
|endpointType|endpointType|**TODO: Add Description**. Possible values are: `default`, `voicemail`, `skypeForBusiness`, `skypeForBusinessVoipPhone`, `unknownFutureValue`.|
|identity|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|languageId|String|**TODO: Add Description**|
|platformId|String|**TODO: Add Description**|
|region|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.participantInfo"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.participantInfo",
  "identity": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "endpointType": "String",
  "region": "String",
  "languageId": "String",
  "countryCode": "String",
  "platformId": "String"
}
```

