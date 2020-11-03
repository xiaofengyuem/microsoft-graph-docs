---
title: "itemFacet resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# itemFacet resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List itemFacets](../api/itemfacet-list.md)|[itemFacet](../resources/itemfacet.md) collection|Get a list of the [itemFacet](../resources/itemfacet.md) objects and their properties.|
|[Create itemFacet](../api/itemfacet-create.md)|[itemFacet](../resources/itemfacet.md)|Create a new [itemFacet](../resources/itemfacet.md) object.|
|[Get itemFacet](../api/itemfacet-get.md)|[itemFacet](../resources/itemfacet.md)|Read the properties and relationships of an [itemFacet](../resources/itemfacet.md) object.|
|[Update itemFacet](../api/itemfacet-update.md)|[itemFacet](../resources/itemfacet.md)|Update the properties of an [itemFacet](../resources/itemfacet.md) object.|
|[Delete itemFacet](../api/itemfacet-delete.md)|None|Deletes an [itemFacet](../resources/itemfacet.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|allowedAudiences|**TODO: Add Description**. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|inference|[inferenceData](../resources/inferencedata.md)|**TODO: Add Description**|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|source|[personDataSources](../resources/persondatasources.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.itemFacet",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.itemFacet",
  "allowedAudiences": "String",
  "inference": {
    "@odata.type": "microsoft.graph.inferenceData"
  },
  "createdDateTime": "String (timestamp)",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "source": {
    "@odata.type": "microsoft.graph.personDataSources"
  }
}
```

