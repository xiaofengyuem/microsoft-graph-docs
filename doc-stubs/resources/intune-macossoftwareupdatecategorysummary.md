---
title: "macOSSoftwareUpdateCategorySummary resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# macOSSoftwareUpdateCategorySummary resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List categorySummaries](../api/intune-macossoftwareupdateaccountsummary-list-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) collection|Get the macOSSoftwareUpdateCategorySummary resources from the categorySummaries navigation property.|
|[Create categorySummaries](../api/intune-macossoftwareupdateaccountsummary-post-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Create a new macOSSoftwareUpdateCategorySummary object.|
|[Update categorySummaries](../api/intune-macossoftwareupdateaccountsummary-update-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Update the properties of a categorySummaries object.|
|[Get categorySummaries](../api/intune-macossoftwareupdateaccountsummary-get-macossoftwareupdatecategorysummary.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[Delete categorySummaries](../api/intune-macossoftwareupdateaccountsummary-delete-categorysummaries.md)|None|Delete a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[List macOSSoftwareUpdateCategorySummaries](../api/intune-macossoftwareupdatecategorysummary-list.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) collection|Get a list of the [macOSSoftwareUpdateCategorySummary](../resources/macossoftwareupdatecategorysummary.md) objects and their properties.|
|[Create macOSSoftwareUpdateCategorySummary](../api/intune-macossoftwareupdatecategorysummary-create.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Create a new [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[Get macOSSoftwareUpdateCategorySummary](../api/intune-macossoftwareupdatecategorysummary-get.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[Update macOSSoftwareUpdateCategorySummary](../api/intune-macossoftwareupdatecategorysummary-update.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Update the properties of a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[Delete macOSSoftwareUpdateCategorySummary](../api/intune-macossoftwareupdatecategorysummary-delete.md)|None|Deletes a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[List updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-list-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) collection|Get the macOSSoftwareUpdateStateSummary resources from the updateStateSummaries navigation property.|
|[Create updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-post-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Create a new macOSSoftwareUpdateStateSummary object.|
|[Get updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-get-macossoftwareupdatestatesummary.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[Update updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-update-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Update the properties of an updateStateSummaries object.|
|[Delete updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-delete-updatestatesummaries.md)|None|Delete a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deviceId|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|failedUpdateCount|Int32|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|
|successfulUpdateCount|Int32|**TODO: Add Description**|
|totalUpdateCount|Int32|**TODO: Add Description**|
|updateCategory|macOSSoftwareUpdateCategory|**TODO: Add Description**. Possible values are: `critical`, `configurationDataFile`, `firmware`, `other`.|
|userId|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|updateStateSummaries|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateCategorySummary",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateCategorySummary",
  "id": "String (identifier)",
  "displayName": "String",
  "deviceId": "String",
  "userId": "String",
  "updateCategory": "String",
  "successfulUpdateCount": "Integer",
  "failedUpdateCount": "Integer",
  "totalUpdateCount": "Integer",
  "lastUpdatedDateTime": "String (timestamp)"
}
```

