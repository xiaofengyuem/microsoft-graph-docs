---
title: "windows10XSCEPCertificateProfile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windows10XSCEPCertificateProfile resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [windows10XCertificateProfile](../resources/windows10xcertificateprofile.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List windows10XSCEPCertificateProfile](../api/windows10xscepcertificateprofile-list.md)|[windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) collection|Get a list of the [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) objects and their properties.|
|[Create windows10XSCEPCertificateProfile](../api/windows10xscepcertificateprofile-create.md)|[windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md)|Create a new [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) object.|
|[Get windows10XSCEPCertificateProfile](../api/windows10xscepcertificateprofile-get.md)|[windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md)|Read the properties and relationships of a [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) object.|
|[Update windows10XSCEPCertificateProfile](../api/windows10xscepcertificateprofile-update.md)|[windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md)|Update the properties of a [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) object.|
|[Delete windows10XSCEPCertificateProfile](../api/windows10xscepcertificateprofile-delete.md)|None|Deletes a [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) object.|
|[List assignments](../api/windows10xscepcertificateprofile-list-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) collection|Get the deviceManagementResourceAccessProfileAssignment resources from the assignments navigation property.|
|[Create assignments](../api/windows10xscepcertificateprofile-post-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Create a new deviceManagementResourceAccessProfileAssignment object.|
|[Get assignments](../api/windows10xscepcertificateprofile-get-devicemanagementresourceaccessprofileassignment.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Read the properties and relationships of a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|
|[Update assignments](../api/windows10xscepcertificateprofile-update-assignments.md)|[deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md)|Update the properties of an assignments object.|
|[Delete assignments](../api/windows10xscepcertificateprofile-delete-assignments.md)|None|Delete a [deviceManagementResourceAccessProfileAssignment](../resources/intune-devicemanagementresourceaccessprofileassignment.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|certificateStore|certificateStore|**TODO: Add Description**. Possible values are: `user`, `machine`.|
|certificateValidityPeriodScale|certificateValidityPeriodScale|**TODO: Add Description**. Possible values are: `days`, `months`, `years`.|
|certificateValidityPeriodValue|Int32|**TODO: Add Description**|
|creationDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|description|String|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|extendedKeyUsages|[extendedKeyUsage](../resources/intune-extendedkeyusage.md) collection|**TODO: Add Description**|
|hashAlgorithm|hashAlgorithms collection|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|keySize|keySize|**TODO: Add Description**. Possible values are: `size1024`, `size2048`, `size4096`.|
|keyStorageProvider|keyStorageProviderOption|**TODO: Add Description**. Possible values are: `useTpmKspOtherwiseUseSoftwareKsp`, `useTpmKspOtherwiseFail`, `usePassportForWorkKspOtherwiseFail`, `useSoftwareKsp`.|
|keyUsage|keyUsages|**TODO: Add Description**. Possible values are: `keyEncipherment`, `digitalSignature`.|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|renewalThresholdPercentage|Int32|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceManagementResourceAccessProfileBase](../resources/intune-devicemanagementresourceaccessprofilebase.md)|
|rootCertificateId|Guid|**TODO: Add Description**|
|scepServerUrls|String collection|**TODO: Add Description**|
|subjectAlternativeNameFormats|[windows10XCustomSubjectAlternativeName](../resources/intune-windows10xcustomsubjectalternativename.md) collection|**TODO: Add Description**|
|subjectNameFormatString|String|**TODO: Add Description**|
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
  "@odata.type": "microsoft.graph.windows10XSCEPCertificateProfile",
  "baseType": "microsoft.graph.windows10XCertificateProfile",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windows10XSCEPCertificateProfile",
  "id": "String (identifier)",
  "version": "Integer",
  "displayName": "String",
  "description": "String",
  "creationDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ],
  "certificateStore": "String",
  "certificateValidityPeriodScale": "String",
  "certificateValidityPeriodValue": "Integer",
  "extendedKeyUsages": [
    {
      "@odata.type": "microsoft.graph.extendedKeyUsage"
    }
  ],
  "hashAlgorithm": [
    "String"
  ],
  "keySize": "String",
  "keyStorageProvider": "String",
  "keyUsage": "String",
  "renewalThresholdPercentage": "Integer",
  "rootCertificateId": "Guid",
  "scepServerUrls": [
    "String"
  ],
  "subjectAlternativeNameFormats": [
    {
      "@odata.type": "microsoft.graph.windows10XCustomSubjectAlternativeName"
    }
  ],
  "subjectNameFormatString": "String"
}
```

