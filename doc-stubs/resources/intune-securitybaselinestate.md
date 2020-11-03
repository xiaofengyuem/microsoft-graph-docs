---
title: "securityBaselineState resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# securityBaselineState resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List securityBaselineStates](../api/intune-manageddevice-list-securitybaselinestates.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md) collection|Get the securityBaselineState resources from the securityBaselineStates navigation property.|
|[Create securityBaselineStates](../api/intune-manageddevice-post-securitybaselinestates.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Create a new securityBaselineState object.|
|[Update securityBaselineStates](../api/intune-manageddevice-update-securitybaselinestates.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Update the properties of a securityBaselineStates object.|
|[Get securityBaselineStates](../api/intune-manageddevice-get-securitybaselinestate.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Read the properties and relationships of a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|
|[Delete securityBaselineStates](../api/intune-manageddevice-delete-securitybaselinestates.md)|None|Delete a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|
|[List securityBaselineStates](../api/intune-securitybaselinestate-list.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md) collection|Get a list of the [securityBaselineState](../resources/securitybaselinestate.md) objects and their properties.|
|[Create securityBaselineState](../api/intune-securitybaselinestate-create.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Create a new [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|
|[Get securityBaselineState](../api/intune-securitybaselinestate-get.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Read the properties and relationships of a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|
|[Update securityBaselineState](../api/intune-securitybaselinestate-update.md)|[securityBaselineState](../resources/intune-securitybaselinestate.md)|Update the properties of a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|
|[Delete securityBaselineState](../api/intune-securitybaselinestate-delete.md)|None|Deletes a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|securityBaselineTemplateId|String|**TODO: Add Description**|
|state|securityBaselineComplianceState|**TODO: Add Description**. Possible values are: `unknown`, `secure`, `notApplicable`, `notSecure`, `error`, `conflict`.|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|settingStates|[securityBaselineSettingState](../resources/intune-securitybaselinesettingstate.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.securityBaselineState",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.securityBaselineState",
  "id": "String (identifier)",
  "securityBaselineTemplateId": "String",
  "userPrincipalName": "String",
  "displayName": "String",
  "state": "String"
}
```

