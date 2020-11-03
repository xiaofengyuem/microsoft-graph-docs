---
title: "defaultManagedAppProtection resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# defaultManagedAppProtection resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [managedAppProtection](../resources/managedappprotection.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List defaultManagedAppProtections](../api/intune-deviceappmanagement-list-defaultmanagedappprotections.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) collection|Get the defaultManagedAppProtection resources from the defaultManagedAppProtections navigation property.|
|[Create defaultManagedAppProtections](../api/intune-deviceappmanagement-post-defaultmanagedappprotections.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Create a new defaultManagedAppProtection object.|
|[Update defaultManagedAppProtections](../api/intune-deviceappmanagement-update-defaultmanagedappprotections.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Update the properties of a defaultManagedAppProtections object.|
|[Get defaultManagedAppProtections](../api/intune-deviceappmanagement-get-defaultmanagedappprotection.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Read the properties and relationships of a [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|
|[Delete defaultManagedAppProtections](../api/intune-deviceappmanagement-delete-defaultmanagedappprotections.md)|None|Delete a [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|
|[List defaultManagedAppProtections](../api/defaultmanagedappprotection-list.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) collection|Get a list of the [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) objects and their properties.|
|[Create defaultManagedAppProtection](../api/defaultmanagedappprotection-create.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Create a new [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|
|[Get defaultManagedAppProtection](../api/defaultmanagedappprotection-get.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Read the properties and relationships of a [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|
|[Update defaultManagedAppProtection](../api/defaultmanagedappprotection-update.md)|[defaultManagedAppProtection](../resources/defaultmanagedappprotection.md)|Update the properties of a [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|
|[Delete defaultManagedAppProtection](../api/defaultmanagedappprotection-delete.md)|None|Deletes a [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAndroidDeviceManufacturers|String|**TODO: Add Description**|
|allowedAndroidDeviceModels|String collection|**TODO: Add Description**|
|allowedDataIngestionLocations|managedAppDataIngestionLocation collection|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `allApps`, `managedApps`, `none`.|
|allowedIosDeviceModels|String|**TODO: Add Description**|
|allowedOutboundClipboardSharingExceptionLength|Int32|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `allApps`, `managedApps`, `none`.|
|appActionIfAndroidDeviceManufacturerNotAllowed|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfAndroidDeviceModelNotAllowed|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfAndroidSafetyNetAppsVerificationFailed|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfAndroidSafetyNetDeviceAttestationFailed|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfDeviceComplianceRequired|managedAppRemediationAction|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `block`, `wipe`, `warn`.|
|appActionIfDeviceLockNotSet|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfIosDeviceModelNotAllowed|managedAppRemediationAction|**TODO: Add Description**. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfMaximumPinRetriesExceeded|managedAppRemediationAction|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `block`, `wipe`, `warn`.|
|appActionIfUnableToAuthenticateUser|managedAppRemediationAction|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `block`, `wipe`, `warn`.|
|appDataEncryptionType|managedAppDataEncryptionType|**TODO: Add Description**. Possible values are: `useDeviceSettings`, `afterDeviceRestart`, `whenDeviceLockedExceptOpenFiles`, `whenDeviceLocked`.|
|biometricAuthenticationBlocked|Boolean|**TODO: Add Description**|
|blockAfterCompanyPortalUpdateDeferralInDays|Int32|**TODO: Add Description**|
|blockDataIngestionIntoOrganizationDocuments|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|contactSyncBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|customBrowserDisplayName|String|**TODO: Add Description**|
|customBrowserPackageId|String|**TODO: Add Description**|
|customBrowserProtocol|String|**TODO: Add Description**|
|customDialerAppDisplayName|String|**TODO: Add Description**|
|customDialerAppPackageId|String|**TODO: Add Description**|
|customDialerAppProtocol|String|**TODO: Add Description**|
|customSettings|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|dataBackupBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|deployedAppCount|Int32|**TODO: Add Description**|
|description|String|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|deviceComplianceRequired|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|deviceLockRequired|Boolean|**TODO: Add Description**|
|dialerRestrictionLevel|managedAppPhoneNumberRedirectLevel|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `allApps`, `managedApps`, `customApp`, `blocked`.|
|disableAppEncryptionIfDeviceEncryptionIsEnabled|Boolean|**TODO: Add Description**|
|disableAppPinIfDevicePinIsSet|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|disableProtectionOfManagedOutboundOpenInData|Boolean|**TODO: Add Description**|
|displayName|String|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|encryptAppData|Boolean|**TODO: Add Description**|
|exemptedAppPackages|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|exemptedAppProtocols|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|faceIdBlocked|Boolean|**TODO: Add Description**|
|filterOpenInToOnlyManagedApps|Boolean|**TODO: Add Description**|
|fingerprintBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|managedBrowser|managedBrowserType|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `notConfigured`, `microsoftEdge`.|
|managedBrowserToOpenLinksRequired|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|maximumAllowedDeviceThreatLevel|managedAppDeviceThreatLevel|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `notConfigured`, `secured`, `low`, `medium`, `high`.|
|maximumPinRetries|Int32|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumPinLength|Int32|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumRequiredAppVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumRequiredCompanyPortalVersion|String|**TODO: Add Description**|
|minimumRequiredOsVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumRequiredPatchVersion|String|**TODO: Add Description**|
|minimumRequiredSdkVersion|String|**TODO: Add Description**|
|minimumWarningAppVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumWarningCompanyPortalVersion|String|**TODO: Add Description**|
|minimumWarningOsVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumWarningPatchVersion|String|**TODO: Add Description**|
|minimumWipeAppVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumWipeCompanyPortalVersion|String|**TODO: Add Description**|
|minimumWipeOsVersion|String|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|minimumWipePatchVersion|String|**TODO: Add Description**|
|minimumWipeSdkVersion|String|**TODO: Add Description**|
|mobileThreatDefenseRemediationAction|managedAppRemediationAction|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `block`, `wipe`, `warn`.|
|notificationRestriction|managedAppNotificationRestriction|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `allow`, `blockOrganizationalData`, `block`.|
|organizationalCredentialsRequired|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|periodBeforePinReset|Duration|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|periodOfflineBeforeAccessCheck|Duration|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|periodOfflineBeforeWipeIsEnforced|Duration|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|periodOnlineBeforeAccessCheck|Duration|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|pinCharacterSet|managedAppPinCharacterSet|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md). Possible values are: `numeric`, `alphanumericAndSymbol`.|
|pinRequired|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|pinRequiredInsteadOfBiometricTimeout|Duration|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|previousPinBlockCount|Int32|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|printBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|protectInboundDataFromUnknownSources|Boolean|**TODO: Add Description**|
|requiredAndroidSafetyNetAppsVerificationType|androidManagedAppSafetyNetAppsVerificationType|**TODO: Add Description**. Possible values are: `none`, `enabled`.|
|requiredAndroidSafetyNetDeviceAttestationType|androidManagedAppSafetyNetDeviceAttestationType|**TODO: Add Description**. Possible values are: `none`, `basicIntegrity`, `basicIntegrityAndDeviceCertification`.|
|requiredAndroidSafetyNetEvaluationType|androidManagedAppSafetyNetEvaluationType|**TODO: Add Description**. Possible values are: `basic`, `hardwareBacked`.|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|saveAsBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|screenCaptureBlocked|Boolean|**TODO: Add Description**|
|simplePinBlocked|Boolean|**TODO: Add Description** Inherited from [managedAppProtection](../resources/managedappprotection.md)|
|thirdPartyKeyboardsBlocked|Boolean|**TODO: Add Description**|
|version|String|**TODO: Add Description** Inherited from [managedAppPolicy](../resources/intune-managedapppolicy.md)|
|warnAfterCompanyPortalUpdateDeferralInDays|Int32|**TODO: Add Description**|
|wipeAfterCompanyPortalUpdateDeferralInDays|Int32|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|apps|[managedMobileApp](../resources/intune-managedmobileapp.md) collection|**TODO: Add Description**|
|deploymentSummary|[managedAppPolicyDeploymentSummary](../resources/intune-managedapppolicydeploymentsummary.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.defaultManagedAppProtection",
  "baseType": "microsoft.graph.managedAppProtection",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.defaultManagedAppProtection",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "createdDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ],
  "version": "String",
  "periodOfflineBeforeAccessCheck": "String (duration)",
  "periodOnlineBeforeAccessCheck": "String (duration)",
  "allowedInboundDataTransferSources": "String",
  "allowedOutboundDataTransferDestinations": "String",
  "organizationalCredentialsRequired": "Boolean",
  "allowedOutboundClipboardSharingLevel": "String",
  "dataBackupBlocked": "Boolean",
  "deviceComplianceRequired": "Boolean",
  "managedBrowserToOpenLinksRequired": "Boolean",
  "saveAsBlocked": "Boolean",
  "periodOfflineBeforeWipeIsEnforced": "String (duration)",
  "pinRequired": "Boolean",
  "maximumPinRetries": "Integer",
  "simplePinBlocked": "Boolean",
  "minimumPinLength": "Integer",
  "pinCharacterSet": "String",
  "periodBeforePinReset": "String (duration)",
  "allowedDataStorageLocations": [
    "String"
  ],
  "contactSyncBlocked": "Boolean",
  "printBlocked": "Boolean",
  "fingerprintBlocked": "Boolean",
  "disableAppPinIfDevicePinIsSet": "Boolean",
  "minimumRequiredOsVersion": "String",
  "minimumWarningOsVersion": "String",
  "minimumRequiredAppVersion": "String",
  "minimumWarningAppVersion": "String",
  "minimumWipeOsVersion": "String",
  "minimumWipeAppVersion": "String",
  "appActionIfDeviceComplianceRequired": "String",
  "appActionIfMaximumPinRetriesExceeded": "String",
  "pinRequiredInsteadOfBiometricTimeout": "String (duration)",
  "allowedOutboundClipboardSharingExceptionLength": "Integer",
  "notificationRestriction": "String",
  "previousPinBlockCount": "Integer",
  "managedBrowser": "String",
  "maximumAllowedDeviceThreatLevel": "String",
  "mobileThreatDefenseRemediationAction": "String",
  "blockDataIngestionIntoOrganizationDocuments": "Boolean",
  "allowedDataIngestionLocations": [
    "String"
  ],
  "appActionIfUnableToAuthenticateUser": "String",
  "dialerRestrictionLevel": "String",
  "appDataEncryptionType": "String",
  "screenCaptureBlocked": "Boolean",
  "encryptAppData": "Boolean",
  "disableAppEncryptionIfDeviceEncryptionIsEnabled": "Boolean",
  "minimumRequiredSdkVersion": "String",
  "customSettings": [
    {
      "@odata.type": "microsoft.graph.keyValuePair"
    }
  ],
  "deployedAppCount": "Integer",
  "minimumRequiredPatchVersion": "String",
  "minimumWarningPatchVersion": "String",
  "exemptedAppProtocols": [
    {
      "@odata.type": "microsoft.graph.keyValuePair"
    }
  ],
  "exemptedAppPackages": [
    {
      "@odata.type": "microsoft.graph.keyValuePair"
    }
  ],
  "faceIdBlocked": "Boolean",
  "minimumWipeSdkVersion": "String",
  "minimumWipePatchVersion": "String",
  "allowedIosDeviceModels": "String",
  "appActionIfIosDeviceModelNotAllowed": "String",
  "allowedAndroidDeviceManufacturers": "String",
  "appActionIfAndroidDeviceManufacturerNotAllowed": "String",
  "thirdPartyKeyboardsBlocked": "Boolean",
  "filterOpenInToOnlyManagedApps": "Boolean",
  "disableProtectionOfManagedOutboundOpenInData": "Boolean",
  "protectInboundDataFromUnknownSources": "Boolean",
  "requiredAndroidSafetyNetDeviceAttestationType": "String",
  "appActionIfAndroidSafetyNetDeviceAttestationFailed": "String",
  "requiredAndroidSafetyNetAppsVerificationType": "String",
  "appActionIfAndroidSafetyNetAppsVerificationFailed": "String",
  "customBrowserProtocol": "String",
  "customBrowserPackageId": "String",
  "customBrowserDisplayName": "String",
  "minimumRequiredCompanyPortalVersion": "String",
  "minimumWarningCompanyPortalVersion": "String",
  "minimumWipeCompanyPortalVersion": "String",
  "allowedAndroidDeviceModels": [
    "String"
  ],
  "appActionIfAndroidDeviceModelNotAllowed": "String",
  "customDialerAppProtocol": "String",
  "customDialerAppPackageId": "String",
  "customDialerAppDisplayName": "String",
  "biometricAuthenticationBlocked": "Boolean",
  "requiredAndroidSafetyNetEvaluationType": "String",
  "blockAfterCompanyPortalUpdateDeferralInDays": "Integer",
  "warnAfterCompanyPortalUpdateDeferralInDays": "Integer",
  "wipeAfterCompanyPortalUpdateDeferralInDays": "Integer",
  "deviceLockRequired": "Boolean",
  "appActionIfDeviceLockNotSet": "String"
}
```

