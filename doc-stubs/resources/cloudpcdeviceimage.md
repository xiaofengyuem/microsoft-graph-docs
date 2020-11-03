---
title: "cloudPcDeviceImage resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# cloudPcDeviceImage resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List cloudPcDeviceImages](../api/cloudmanageddesktop-list-cloudpcdeviceimages.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) collection|Get the cloudPcDeviceImage resources from the cloudPcDeviceImages navigation property.|
|[Create cloudPcDeviceImages](../api/cloudmanageddesktop-post-cloudpcdeviceimages.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Create a new cloudPcDeviceImage object.|
|[Update cloudPcDeviceImages](../api/cloudmanageddesktop-update-cloudpcdeviceimages.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Update the properties of a cloudPcDeviceImages object.|
|[Get cloudPcDeviceImages](../api/cloudmanageddesktop-get-cloudpcdeviceimage.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Read the properties and relationships of a [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[Delete cloudPcDeviceImages](../api/cloudmanageddesktop-delete-cloudpcdeviceimages.md)|None|Delete a [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[List cloudPcDeviceImages](../api/cloudpcdeviceimage-list.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) collection|Get a list of the [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) objects and their properties.|
|[Create cloudPcDeviceImage](../api/cloudpcdeviceimage-create.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Create a new [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[Get cloudPcDeviceImage](../api/cloudpcdeviceimage-get.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Read the properties and relationships of a [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[Update cloudPcDeviceImage](../api/cloudpcdeviceimage-update.md)|[cloudPcDeviceImage](../resources/cloudpcdeviceimage.md)|Update the properties of a [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[Delete cloudPcDeviceImage](../api/cloudpcdeviceimage-delete.md)|None|Deletes a [cloudPcDeviceImage](../resources/cloudpcdeviceimage.md) object.|
|[getSourceImages](../api/cloudpcdeviceimage-getsourceimages.md)|[cloudPcSourceDeviceImage](../resources/cloudpcsourcedeviceimage.md) collection|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|operatingSystem|String|**TODO: Add Description**|
|osBuildNumber|String|**TODO: Add Description**|
|sourceImageResourceId|String|**TODO: Add Description**|
|status|cloudPcDeviceImageStatus|**TODO: Add Description**. Possible values are: `pending`, `ready`, `failed`.|
|statusDetails|cloudPcDeviceImageStatusDetails|**TODO: Add Description**. Possible values are: `internalServerError`, `sourceImageNotFound`.|
|version|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.cloudPcDeviceImage",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.cloudPcDeviceImage",
  "id": "String (identifier)",
  "displayName": "String",
  "operatingSystem": "String",
  "osBuildNumber": "String",
  "version": "String",
  "lastModifiedDateTime": "String (timestamp)",
  "status": "String",
  "statusDetails": "String",
  "sourceImageResourceId": "String"
}
```

