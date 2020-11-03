---
title: "hardwareInformation resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# hardwareInformation resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|batteryChargeCycles|Int32|**TODO: Add Description**|
|batteryHealthPercentage|Int32|**TODO: Add Description**|
|batterySerialNumber|String|**TODO: Add Description**|
|cellularTechnology|String|**TODO: Add Description**|
|deviceFullQualifiedDomainName|String|**TODO: Add Description**|
|deviceGuardLocalSystemAuthorityCredentialGuardState|deviceGuardLocalSystemAuthorityCredentialGuardState|**TODO: Add Description**. Possible values are: `running`, `rebootRequired`, `notLicensed`, `notConfigured`, `virtualizationBasedSecurityNotRunning`.|
|deviceGuardVirtualizationBasedSecurityHardwareRequirementState|deviceGuardVirtualizationBasedSecurityHardwareRequirementState|**TODO: Add Description**. Possible values are: `meetHardwareRequirements`, `secureBootRequired`, `dmaProtectionRequired`, `hyperVNotSupportedForGuestVM`, `hyperVNotAvailable`.|
|deviceGuardVirtualizationBasedSecurityState|deviceGuardVirtualizationBasedSecurityState|**TODO: Add Description**. Possible values are: `running`, `rebootRequired`, `require64BitArchitecture`, `notLicensed`, `notConfigured`, `doesNotMeetHardwareRequirements`, `other`.|
|freeStorageSpace|Int64|**TODO: Add Description**|
|imei|String|**TODO: Add Description**|
|ipAddressV4|String|**TODO: Add Description**|
|isEncrypted|Boolean|**TODO: Add Description**|
|isSharedDevice|Boolean|**TODO: Add Description**|
|isSupervised|Boolean|**TODO: Add Description**|
|manufacturer|String|**TODO: Add Description**|
|meid|String|**TODO: Add Description**|
|model|String|**TODO: Add Description**|
|operatingSystemEdition|String|**TODO: Add Description**|
|operatingSystemLanguage|String|**TODO: Add Description**|
|operatingSystemProductType|Int32|**TODO: Add Description**|
|osBuildNumber|String|**TODO: Add Description**|
|phoneNumber|String|**TODO: Add Description**|
|serialNumber|String|**TODO: Add Description**|
|sharedDeviceCachedUsers|[sharedAppleDeviceUser](../resources/intune-sharedappledeviceuser.md) collection|**TODO: Add Description**|
|subnetAddress|String|**TODO: Add Description**|
|subscriberCarrier|String|**TODO: Add Description**|
|totalStorageSpace|Int64|**TODO: Add Description**|
|tpmSpecificationVersion|String|**TODO: Add Description**|
|wifiMac|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.hardwareInformation"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.hardwareInformation",
  "serialNumber": "String",
  "totalStorageSpace": "Integer",
  "freeStorageSpace": "Integer",
  "imei": "String",
  "meid": "String",
  "manufacturer": "String",
  "model": "String",
  "phoneNumber": "String",
  "subscriberCarrier": "String",
  "cellularTechnology": "String",
  "wifiMac": "String",
  "operatingSystemLanguage": "String",
  "isSupervised": "Boolean",
  "isEncrypted": "Boolean",
  "batterySerialNumber": "String",
  "batteryHealthPercentage": "Integer",
  "batteryChargeCycles": "Integer",
  "isSharedDevice": "Boolean",
  "sharedDeviceCachedUsers": [
    {
      "@odata.type": "microsoft.graph.sharedAppleDeviceUser"
    }
  ],
  "tpmSpecificationVersion": "String",
  "operatingSystemEdition": "String",
  "deviceFullQualifiedDomainName": "String",
  "deviceGuardVirtualizationBasedSecurityHardwareRequirementState": "String",
  "deviceGuardVirtualizationBasedSecurityState": "String",
  "deviceGuardLocalSystemAuthorityCredentialGuardState": "String",
  "osBuildNumber": "String",
  "operatingSystemProductType": "Integer",
  "ipAddressV4": "String",
  "subnetAddress": "String"
}
```

