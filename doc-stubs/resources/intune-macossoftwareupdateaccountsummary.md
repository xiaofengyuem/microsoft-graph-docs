---
title: "macOSSoftwareUpdateAccountSummary resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# macOSSoftwareUpdateAccountSummary resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List macOSSoftwareUpdateAccountSummaries](../api/intune-devicemanagement-list-macossoftwareupdateaccountsummaries.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) collection|Get the macOSSoftwareUpdateAccountSummary resources from the macOSSoftwareUpdateAccountSummaries navigation property.|
|[Create macOSSoftwareUpdateAccountSummaries](../api/intune-devicemanagement-post-macossoftwareupdateaccountsummaries.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Create a new macOSSoftwareUpdateAccountSummary object.|
|[Update macOSSoftwareUpdateAccountSummaries](../api/intune-devicemanagement-update-macossoftwareupdateaccountsummaries.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Update the properties of a macOSSoftwareUpdateAccountSummaries object.|
|[Get macOSSoftwareUpdateAccountSummaries](../api/intune-devicemanagement-get-macossoftwareupdateaccountsummary.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[Delete macOSSoftwareUpdateAccountSummaries](../api/intune-devicemanagement-delete-macossoftwareupdateaccountsummaries.md)|None|Delete a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[List macOSSoftwareUpdateAccountSummaries](../api/intune-macossoftwareupdateaccountsummary-list.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) collection|Get a list of the [macOSSoftwareUpdateAccountSummary](../resources/macossoftwareupdateaccountsummary.md) objects and their properties.|
|[Create macOSSoftwareUpdateAccountSummary](../api/intune-macossoftwareupdateaccountsummary-create.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Create a new [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[Get macOSSoftwareUpdateAccountSummary](../api/intune-macossoftwareupdateaccountsummary-get.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[Update macOSSoftwareUpdateAccountSummary](../api/intune-macossoftwareupdateaccountsummary-update.md)|[macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md)|Update the properties of a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[Delete macOSSoftwareUpdateAccountSummary](../api/intune-macossoftwareupdateaccountsummary-delete.md)|None|Deletes a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.|
|[List categorySummaries](../api/intune-macossoftwareupdateaccountsummary-list-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) collection|Get the macOSSoftwareUpdateCategorySummary resources from the categorySummaries navigation property.|
|[Create categorySummaries](../api/intune-macossoftwareupdateaccountsummary-post-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Create a new macOSSoftwareUpdateCategorySummary object.|
|[Get categorySummaries](../api/intune-macossoftwareupdateaccountsummary-get-macossoftwareupdatecategorysummary.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Read the properties and relationships of a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|
|[Update categorySummaries](../api/intune-macossoftwareupdateaccountsummary-update-categorysummaries.md)|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md)|Update the properties of a categorySummaries object.|
|[Delete categorySummaries](../api/intune-macossoftwareupdateaccountsummary-delete-categorysummaries.md)|None|Delete a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deviceId|String|**TODO: Add Description**|
|deviceName|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|failedUpdateCount|Int32|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|
|osVersion|String|**TODO: Add Description**|
|successfulUpdateCount|Int32|**TODO: Add Description**|
|totalUpdateCount|Int32|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|categorySummaries|[macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateAccountSummary",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateAccountSummary",
  "id": "String (identifier)",
  "displayName": "String",
  "deviceId": "String",
  "userId": "String",
  "deviceName": "String",
  "userPrincipalName": "String",
  "osVersion": "String",
  "successfulUpdateCount": "Integer",
  "failedUpdateCount": "Integer",
  "totalUpdateCount": "Integer",
  "lastUpdatedDateTime": "String (timestamp)"
}
```

