---
title: "macOSSoftwareUpdateStateSummary resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# macOSSoftwareUpdateStateSummary resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-list-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) collection|Get the macOSSoftwareUpdateStateSummary resources from the updateStateSummaries navigation property.|
|[Create updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-post-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Create a new macOSSoftwareUpdateStateSummary object.|
|[Update updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-update-updatestatesummaries.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Update the properties of an updateStateSummaries object.|
|[Get updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-get-macossoftwareupdatestatesummary.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[Delete updateStateSummaries](../api/intune-macossoftwareupdatecategorysummary-delete-updatestatesummaries.md)|None|Delete a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[List macOSSoftwareUpdateStateSummaries](../api/intune-macossoftwareupdatestatesummary-list.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) collection|Get a list of the [macOSSoftwareUpdateStateSummary](../resources/macossoftwareupdatestatesummary.md) objects and their properties.|
|[Create macOSSoftwareUpdateStateSummary](../api/intune-macossoftwareupdatestatesummary-create.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Create a new [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[Get macOSSoftwareUpdateStateSummary](../api/intune-macossoftwareupdatestatesummary-get.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[Update macOSSoftwareUpdateStateSummary](../api/intune-macossoftwareupdatestatesummary-update.md)|[macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md)|Update the properties of a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|
|[Delete macOSSoftwareUpdateStateSummary](../api/intune-macossoftwareupdatestatesummary-delete.md)|None|Deletes a [macOSSoftwareUpdateStateSummary](../resources/intune-macossoftwareupdatestatesummary.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|
|productKey|String|**TODO: Add Description**|
|state|macOSSoftwareUpdateState|**TODO: Add Description**. Possible values are: `success`, `downloading`, `downloaded`, `installing`, `idle`, `available`, `scheduled`, `downloadFailed`, `downloadInsufficientSpace`, `downloadInsufficientPower`, `downloadInsufficientNetwork`, `installInsufficientSpace`, `installInsufficientPower`, `installFailed`, `commandFailed`.|
|updateCategory|macOSSoftwareUpdateCategory|**TODO: Add Description**. Possible values are: `critical`, `configurationDataFile`, `firmware`, `other`.|
|updateVersion|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateStateSummary",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateStateSummary",
  "id": "String (identifier)",
  "displayName": "String",
  "productKey": "String",
  "updateCategory": "String",
  "updateVersion": "String",
  "state": "String",
  "lastUpdatedDateTime": "String (timestamp)"
}
```

