---
title: "androidDeviceOwnerEnrollmentProfile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# androidDeviceOwnerEnrollmentProfile resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List androidDeviceOwnerEnrollmentProfiles](../api/intune-devicemanagement-list-androiddeviceownerenrollmentprofiles.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) collection|Get the androidDeviceOwnerEnrollmentProfile resources from the androidDeviceOwnerEnrollmentProfiles navigation property.|
|[Create androidDeviceOwnerEnrollmentProfiles](../api/intune-devicemanagement-post-androiddeviceownerenrollmentprofiles.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Create a new androidDeviceOwnerEnrollmentProfile object.|
|[Update androidDeviceOwnerEnrollmentProfiles](../api/intune-devicemanagement-update-androiddeviceownerenrollmentprofiles.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Update the properties of an androidDeviceOwnerEnrollmentProfiles object.|
|[Get androidDeviceOwnerEnrollmentProfiles](../api/intune-devicemanagement-get-androiddeviceownerenrollmentprofile.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Read the properties and relationships of an [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|
|[Delete androidDeviceOwnerEnrollmentProfiles](../api/intune-devicemanagement-delete-androiddeviceownerenrollmentprofiles.md)|None|Delete an [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|
|[List androidDeviceOwnerEnrollmentProfiles](../api/intune-androiddeviceownerenrollmentprofile-list.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) collection|Get a list of the [androidDeviceOwnerEnrollmentProfile](../resources/androiddeviceownerenrollmentprofile.md) objects and their properties.|
|[Create androidDeviceOwnerEnrollmentProfile](../api/intune-androiddeviceownerenrollmentprofile-create.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Create a new [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|
|[Get androidDeviceOwnerEnrollmentProfile](../api/intune-androiddeviceownerenrollmentprofile-get.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Read the properties and relationships of an [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|
|[Update androidDeviceOwnerEnrollmentProfile](../api/intune-androiddeviceownerenrollmentprofile-update.md)|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md)|Update the properties of an [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|
|[Delete androidDeviceOwnerEnrollmentProfile](../api/intune-androiddeviceownerenrollmentprofile-delete.md)|None|Deletes an [androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|accountId|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|enrolledDeviceCount|Int32|**TODO: Add Description**|
|enrollmentMode|androidDeviceOwnerEnrollmentMode|**TODO: Add Description**. Possible values are: `corporateOwnedDedicatedDevice`, `corporateOwnedFullyManaged`, `corporateOwnedWorkProfile`.|
|enrollmentTokenType|androidDeviceOwnerEnrollmentTokenType|**TODO: Add Description**. Possible values are: `default`, `corporateOwnedDedicatedDeviceWithAzureADSharedMode`.|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|qrCodeContent|String|**TODO: Add Description**|
|qrCodeImage|[mimeContent](../resources/intune-mimecontent.md)|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description**|
|tokenCreationDateTime|DateTimeOffset|**TODO: Add Description**|
|tokenExpirationDateTime|DateTimeOffset|**TODO: Add Description**|
|tokenValue|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.androidDeviceOwnerEnrollmentProfile",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.androidDeviceOwnerEnrollmentProfile",
  "id": "String (identifier)",
  "accountId": "String",
  "displayName": "String",
  "description": "String",
  "enrollmentMode": "String",
  "enrollmentTokenType": "String",
  "createdDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "tokenValue": "String",
  "tokenCreationDateTime": "String (timestamp)",
  "tokenExpirationDateTime": "String (timestamp)",
  "enrolledDeviceCount": "Integer",
  "qrCodeContent": "String",
  "qrCodeImage": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "roleScopeTagIds": [
    "String"
  ]
}
```

