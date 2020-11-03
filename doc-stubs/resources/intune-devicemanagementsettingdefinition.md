---
title: "deviceManagementSettingDefinition resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagementSettingDefinition resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List settingDefinitions](../api/intune-devicemanagementsettingcategory-list-settingdefinitions.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) collection|Get the deviceManagementSettingDefinition resources from the settingDefinitions navigation property.|
|[Create settingDefinitions](../api/intune-devicemanagementsettingcategory-post-settingdefinitions.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Create a new deviceManagementSettingDefinition object.|
|[Update settingDefinitions](../api/intune-devicemanagementsettingcategory-update-settingdefinitions.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Update the properties of a settingDefinitions object.|
|[Get settingDefinitions](../api/intune-devicemanagementsettingcategory-get-devicemanagementsettingdefinition.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Read the properties and relationships of a [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|
|[Delete settingDefinitions](../api/intune-devicemanagementsettingcategory-delete-settingdefinitions.md)|None|Delete a [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|
|[List deviceManagementSettingDefinitions](../api/intune-devicemanagementsettingdefinition-list.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) collection|Get a list of the [deviceManagementSettingDefinition](../resources/devicemanagementsettingdefinition.md) objects and their properties.|
|[Create deviceManagementSettingDefinition](../api/intune-devicemanagementsettingdefinition-create.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Create a new [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|
|[Get deviceManagementSettingDefinition](../api/intune-devicemanagementsettingdefinition-get.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Read the properties and relationships of a [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|
|[Update deviceManagementSettingDefinition](../api/intune-devicemanagementsettingdefinition-update.md)|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md)|Update the properties of a [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|
|[Delete deviceManagementSettingDefinition](../api/intune-devicemanagementsettingdefinition-delete.md)|None|Deletes a [deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|constraints|[deviceManagementConstraint](../resources/intune-devicemanagementconstraint.md) collection|**TODO: Add Description**|
|dependencies|[deviceManagementSettingDependency](../resources/intune-devicemanagementsettingdependency.md) collection|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|documentationUrl|String|**TODO: Add Description**|
|headerSubtitle|String|**TODO: Add Description**|
|headerTitle|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|isTopLevel|Boolean|**TODO: Add Description**|
|keywords|String collection|**TODO: Add Description**|
|placeholderText|String|**TODO: Add Description**|
|valueType|deviceManangementIntentValueType|**TODO: Add Description**. Possible values are: `integer`, `boolean`, `string`, `complex`, `collection`, `abstractComplex`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementSettingDefinition",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementSettingDefinition",
  "id": "String (identifier)",
  "valueType": "String",
  "displayName": "String",
  "isTopLevel": "Boolean",
  "description": "String",
  "placeholderText": "String",
  "documentationUrl": "String",
  "headerTitle": "String",
  "headerSubtitle": "String",
  "keywords": [
    "String"
  ],
  "constraints": [
    {
      "@odata.type": "microsoft.graph.deviceManagementSettingAppConstraint"
    }
  ],
  "dependencies": [
    {
      "@odata.type": "microsoft.graph.deviceManagementSettingDependency"
    }
  ]
}
```

