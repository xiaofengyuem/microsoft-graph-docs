---
title: "windows10XVpnConfiguration resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windows10XVpnConfiguration resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [deviceManagementResourceAccessProfileBase](../resources/devicemanagementresourceaccessprofilebase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List windows10XVpnConfiguration](../api/windows10xvpnconfiguration-list.md)|[windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) collection|Get a list of the [windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) objects and their properties.|
|[Create windows10XVpnConfiguration](../api/windows10xvpnconfiguration-create.md)|[windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md)|Create a new [windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) object.|
|[Get windows10XVpnConfiguration](../api/windows10xvpnconfiguration-get.md)|[windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md)|Read the properties and relationships of a [windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) object.|
|[Update windows10XVpnConfiguration](../api/windows10xvpnconfiguration-update.md)|[windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md)|Update the properties of a [windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) object.|
|[Delete windows10XVpnConfiguration](../api/windows10xvpnconfiguration-delete.md)|None|Deletes a [windows10XVpnConfiguration](../resources/windows10xvpnconfiguration.md) object.|
|[assign](../api/windows10xvpnconfiguration-assign.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|**TODO: Add Description**|
|[List assignments](../api/windows10xvpnconfiguration-list-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|Get the deviceManagementResourceAccessProfileAssignment resources from the assignments navigation property.|
|[Create assignments](../api/windows10xvpnconfiguration-post-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Create a new deviceManagementResourceAccessProfileAssignment object.|
|[Get assignments](../api/windows10xvpnconfiguration-get-devicemanagementresourceaccessprofileassignment.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Read the properties and relationships of a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|
|[Update assignments](../api/windows10xvpnconfiguration-update-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Update the properties of an assignments object.|
|[Delete assignments](../api/windows10xvpnconfiguration-delete-assignments.md)|None|Delete a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|authenticationCertificateId|Guid|**TODO: Add Description**|
|creationDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|customXml|Binary|**TODO: Add Description**|
|customXmlFileName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|version|Int32|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|assignments|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/devicemanagementresourceaccessprofilebase.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windows10XVpnConfiguration",
  "baseType": "microsoft.graph.deviceManagementResourceAccessProfileBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windows10XVpnConfiguration",
  "id": "String (identifier)",
  "version": "Integer",
  "displayName": "String",
  "description": "String",
  "creationDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ],
  "authenticationCertificateId": "Guid",
  "customXmlFileName": "String",
  "customXml": "Binary"
}
```

