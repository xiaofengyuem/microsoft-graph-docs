---
title: "ediscoveryCase resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# ediscoveryCase resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List cases](../api/ediscovery-list-cases.md)|[ediscoveryCase](../resources/ediscoverycase.md) collection|Get the ediscoveryCase resources from the cases navigation property.|
|[Create cases](../api/ediscovery-post-cases.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Create a new ediscoveryCase object.|
|[Update cases](../api/ediscovery-update-cases.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Update the properties of a cases object.|
|[Get cases](../api/ediscovery-get-ediscoverycase.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Read the properties and relationships of an [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[Delete cases](../api/ediscovery-delete-cases.md)|None|Delete an [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[List ediscoveryCases](../api/ediscoverycase-list.md)|[ediscoveryCase](../resources/ediscoverycase.md) collection|Get a list of the [ediscoveryCase](../resources/ediscoverycase.md) objects and their properties.|
|[Create ediscoveryCase](../api/ediscoverycase-create.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Create a new [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[Get ediscoveryCase](../api/ediscoverycase-get.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Read the properties and relationships of an [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[Update ediscoveryCase](../api/ediscoverycase-update.md)|[ediscoveryCase](../resources/ediscoverycase.md)|Update the properties of an [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[Delete ediscoveryCase](../api/ediscoverycase-delete.md)|None|Deletes an [ediscoveryCase](../resources/ediscoverycase.md) object.|
|[List custodians](../api/ediscoverycase-list-custodians.md)|[custodian](../resources/custodian.md) collection|Get the custodian resources from the custodians navigation property.|
|[Create custodians](../api/ediscoverycase-post-custodians.md)|[custodian](../resources/custodian.md)|Create a new custodian object.|
|[Get custodians](../api/ediscoverycase-get-custodian.md)|[custodian](../resources/custodian.md)|Read the properties and relationships of a [custodian](../resources/custodian.md) object.|
|[Update custodians](../api/ediscoverycase-update-custodians.md)|[custodian](../resources/custodian.md)|Update the properties of a custodians object.|
|[Delete custodians](../api/ediscoverycase-delete-custodians.md)|None|Delete a [custodian](../resources/custodian.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|closedDateTime|DateTimeOffset|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|status|caseStatus|**TODO: Add Description**. Possible values are: `unknown`, `active`, `pendingDelete`, `closing`, `closed`, `closedWithError`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|custodians|[custodian](../resources/custodian.md) collection|**TODO: Add Description**|
|reviewSets|[reviewSet](../resources/reviewset.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.ediscoveryCase",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.ediscoveryCase",
  "id": "String (identifier)",
  "description": "String",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)",
  "status": "String",
  "closedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "closedDateTime": "String (timestamp)",
  "externalId": "String",
  "displayName": "String",
  "createdDateTime": "String (timestamp)"
}
```

