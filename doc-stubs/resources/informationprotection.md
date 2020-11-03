---
title: "informationProtection resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# informationProtection resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List informationProtection](../api/user-list-informationprotection.md)|[informationProtection](../resources/informationprotection.md) collection|Get the informationProtection resources from the informationProtection navigation property.|
|[Create informationProtection](../api/user-post-informationprotection.md)|[informationProtection](../resources/informationprotection.md)|Create a new informationProtection object.|
|[Update informationProtection](../api/user-update-informationprotection.md)|[informationProtection](../resources/informationprotection.md)|Update the properties of an informationProtection object.|
|[Get informationProtection](../api/user-get-informationprotection.md)|[informationProtection](../resources/informationprotection.md)|Read the properties and relationships of an [informationProtection](../resources/informationprotection.md) object.|
|[Delete informationProtection](../api/user-delete-informationprotection.md)|None|Delete an [informationProtection](../resources/informationprotection.md) object.|
|[List informationProtections](../api/informationprotection-list.md)|[informationProtection](../resources/informationprotection.md) collection|Get a list of the [informationProtection](../resources/informationprotection.md) objects and their properties.|
|[Create informationProtection](../api/informationprotection-create.md)|[informationProtection](../resources/informationprotection.md)|Create a new [informationProtection](../resources/informationprotection.md) object.|
|[Get informationProtection](../api/informationprotection-get.md)|[informationProtection](../resources/informationprotection.md)|Read the properties and relationships of an [informationProtection](../resources/informationprotection.md) object.|
|[Update informationProtection](../api/informationprotection-update.md)|[informationProtection](../resources/informationprotection.md)|Update the properties of an [informationProtection](../resources/informationprotection.md) object.|
|[Delete informationProtection](../api/informationprotection-delete.md)|None|Deletes an [informationProtection](../resources/informationprotection.md) object.|
|[List bitlocker](../api/informationprotection-list-bitlocker.md)|[bitlocker](../resources/bitlocker.md) collection|Get the bitlocker resources from the bitlocker navigation property.|
|[Create bitlocker](../api/informationprotection-post-bitlocker.md)|[bitlocker](../resources/bitlocker.md)|Create a new bitlocker object.|
|[Get bitlocker](../api/informationprotection-get-bitlocker.md)|[bitlocker](../resources/bitlocker.md)|Read the properties and relationships of a [bitlocker](../resources/bitlocker.md) object.|
|[Update bitlocker](../api/informationprotection-update-bitlocker.md)|[bitlocker](../resources/bitlocker.md)|Update the properties of a bitlocker object.|
|[Delete bitlocker](../api/informationprotection-delete-bitlocker.md)|None|Delete a [bitlocker](../resources/bitlocker.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|bitlocker|[bitlocker](../resources/bitlocker.md)|**TODO: Add Description**|
|dataLossPreventionPolicies|[dataLossPreventionPolicy](../resources/datalosspreventionpolicy.md) collection|**TODO: Add Description**|
|policy|[informationProtectionPolicy](../resources/informationprotectionpolicy.md)|**TODO: Add Description**|
|sensitivityLabels|[sensitivityLabel](../resources/sensitivitylabel.md) collection|**TODO: Add Description**|
|sensitivityPolicySettings|[sensitivityPolicySettings](../resources/sensitivitypolicysettings.md)|**TODO: Add Description**|
|threatAssessmentRequests|[threatAssessmentRequest](../resources/threatassessmentrequest.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.informationProtection",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.informationProtection"
}
```

