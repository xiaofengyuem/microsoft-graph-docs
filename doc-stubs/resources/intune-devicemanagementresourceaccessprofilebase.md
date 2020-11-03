---
title: "deviceManagementResourceAccessProfileBase resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagementResourceAccessProfileBase resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List resourceAccessProfiles](../api/intune-devicemanagement-list-resourceaccessprofiles.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) collection|Get the deviceManagementResourceAccessProfileBase resources from the resourceAccessProfiles navigation property.|
|[Create resourceAccessProfiles](../api/intune-devicemanagement-post-resourceaccessprofiles.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Create a new deviceManagementResourceAccessProfileBase object.|
|[Update resourceAccessProfiles](../api/intune-devicemanagement-update-resourceaccessprofiles.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Update the properties of a resourceAccessProfiles object.|
|[Get resourceAccessProfiles](../api/intune-devicemanagement-get-devicemanagementresourceaccessprofilebase.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Read the properties and relationships of a [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[Delete resourceAccessProfiles](../api/intune-devicemanagement-delete-resourceaccessprofiles.md)|None|Delete a [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[List deviceManagementResourceAccessProfileBases](../api/intune-devicemanagementresourceaccessprofilebase-list.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) collection|Get a list of the [deviceManagementResourceAccessProfileBase](../resources/devicemanagementresourceaccessprofilebase.md) objects and their properties.|
|[Create deviceManagementResourceAccessProfileBase](../api/intune-devicemanagementresourceaccessprofilebase-create.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Create a new [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[Get deviceManagementResourceAccessProfileBase](../api/intune-devicemanagementresourceaccessprofilebase-get.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Read the properties and relationships of a [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[Update deviceManagementResourceAccessProfileBase](../api/intune-devicemanagementresourceaccessprofilebase-update.md)|[deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|Update the properties of a [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[Delete deviceManagementResourceAccessProfileBase](../api/intune-devicemanagementresourceaccessprofilebase-delete.md)|None|Deletes a [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md) object.|
|[assign](../api/intune-devicemanagementresourceaccessprofilebase-assign.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|**TODO: Add Description**|
|[List assignments](../api/intune-devicemanagementresourceaccessprofilebase-list-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|Get the deviceManagementResourceAccessProfileAssignment resources from the assignments navigation property.|
|[Create assignments](../api/intune-devicemanagementresourceaccessprofilebase-post-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Create a new deviceManagementResourceAccessProfileAssignment object.|
|[Get assignments](../api/intune-devicemanagementresourceaccessprofilebase-get-devicemanagementresourceaccessprofileassignment.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Read the properties and relationships of a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|
|[Update assignments](../api/intune-devicemanagementresourceaccessprofilebase-update-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Update the properties of an assignments object.|
|[Delete assignments](../api/intune-devicemanagementresourceaccessprofilebase-delete-assignments.md)|None|Delete a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description**|
|version|Int32|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|assignments|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementResourceAccessProfileBase",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementResourceAccessProfileBase",
  "id": "String (identifier)",
  "version": "Integer",
  "displayName": "String",
  "description": "String",
  "creationDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ]
}
```

