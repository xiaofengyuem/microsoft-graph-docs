---
title: "List defaultManagedAppProtections"
description: "Get a list of the defaultManagedAppProtection objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List defaultManagedAppProtections
Namespace: microsoft.graph

Get a list of the [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /deviceAppManagement/defaultManagedAppProtections
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [defaultManagedAppProtection](../resources/defaultmanagedappprotection.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_defaultmanagedappprotection"
}
-->
``` http
GET https://graph.microsoft.com/beta/deviceAppManagement/defaultManagedAppProtections
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.defaultManagedAppProtection)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.defaultManagedAppProtection",
      "id": "57c8da2d-da2d-57c8-2dda-c8572ddac857",
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
  ]
}
```

