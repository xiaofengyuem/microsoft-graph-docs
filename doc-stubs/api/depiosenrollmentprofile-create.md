---
title: "Create depIOSEnrollmentProfile"
description: "Create a new depIOSEnrollmentProfile object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create depIOSEnrollmentProfile
Namespace: microsoft.graph

Create a new [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md) object.

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
POST ** Collection URI for microsoft.graph.depIOSEnrollmentProfile not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md) object.

The following table shows the properties that are required when you create the [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|description|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|requiresUserAuthentication|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|configurationEndpointUrl|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|enableAuthenticationViaCompanyPortal|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|isDefault|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supervisedModeEnabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supportDepartment|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|isMandatory|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|locationDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supportPhoneNumber|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|profileRemovalDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|restoreBlocked|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|appleIdDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|termsAndConditionsDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|touchIdDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|applePayDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|siriDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|diagnosticsDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|displayToneSetupDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|privacyPaneDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|screenTimeScreenDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|deviceNameTemplate|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|configurationWebUrl|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|iTunesPairingMode|iTunesPairingMode|**TODO: Add Description**. Possible values are: `disallow`, `allow`, `requiresCertificate`.|
|managementCertificates|[managementCertificateWithThumbprint](../resources/intune-managementcertificatewiththumbprint.md) collection|**TODO: Add Description**|
|restoreFromAndroidDisabled|Boolean|**TODO: Add Description**|
|awaitDeviceConfiguredConfirmation|Boolean|**TODO: Add Description**|
|sharedIPadMaximumUserCount|Int32|**TODO: Add Description**|
|enableSharedIPad|Boolean|**TODO: Add Description**|
|companyPortalVppTokenId|String|**TODO: Add Description**|
|enableSingleAppEnrollmentMode|Boolean|**TODO: Add Description**|
|homeButtonScreenDisabled|Boolean|**TODO: Add Description**|
|iMessageAndFaceTimeScreenDisabled|Boolean|**TODO: Add Description**|
|onBoardingScreenDisabled|Boolean|**TODO: Add Description**|
|simSetupScreenDisabled|Boolean|**TODO: Add Description**|
|softwareUpdateScreenDisabled|Boolean|**TODO: Add Description**|
|watchMigrationScreenDisabled|Boolean|**TODO: Add Description**|
|appearanceScreenDisabled|Boolean|**TODO: Add Description**|
|expressLanguageScreenDisabled|Boolean|**TODO: Add Description**|
|preferredLanguageScreenDisabled|Boolean|**TODO: Add Description**|
|deviceToDeviceMigrationDisabled|Boolean|**TODO: Add Description**|
|welcomeScreenDisabled|Boolean|**TODO: Add Description**|
|passCodeDisabled|Boolean|**TODO: Add Description**|
|zoomDisabled|Boolean|**TODO: Add Description**|
|restoreCompletedScreenDisabled|Boolean|**TODO: Add Description**|
|updateCompleteScreenDisabled|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_depiosenrollmentprofile_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.depIOSEnrollmentProfile not found
Content-Type: application/json
Content-length: 2075

{
  "@odata.type": "#microsoft.graph.depIOSEnrollmentProfile",
  "displayName": "String",
  "description": "String",
  "requiresUserAuthentication": "Boolean",
  "configurationEndpointUrl": "String",
  "enableAuthenticationViaCompanyPortal": "Boolean",
  "requireCompanyPortalOnSetupAssistantEnrolledDevices": "Boolean",
  "isDefault": "Boolean",
  "supervisedModeEnabled": "Boolean",
  "supportDepartment": "String",
  "isMandatory": "Boolean",
  "locationDisabled": "Boolean",
  "supportPhoneNumber": "String",
  "profileRemovalDisabled": "Boolean",
  "restoreBlocked": "Boolean",
  "appleIdDisabled": "Boolean",
  "termsAndConditionsDisabled": "Boolean",
  "touchIdDisabled": "Boolean",
  "applePayDisabled": "Boolean",
  "siriDisabled": "Boolean",
  "diagnosticsDisabled": "Boolean",
  "displayToneSetupDisabled": "Boolean",
  "privacyPaneDisabled": "Boolean",
  "screenTimeScreenDisabled": "Boolean",
  "deviceNameTemplate": "String",
  "configurationWebUrl": "Boolean",
  "iTunesPairingMode": "String",
  "managementCertificates": [
    {
      "@odata.type": "microsoft.graph.managementCertificateWithThumbprint"
    }
  ],
  "restoreFromAndroidDisabled": "Boolean",
  "awaitDeviceConfiguredConfirmation": "Boolean",
  "sharedIPadMaximumUserCount": "Integer",
  "enableSharedIPad": "Boolean",
  "companyPortalVppTokenId": "String",
  "enableSingleAppEnrollmentMode": "Boolean",
  "homeButtonScreenDisabled": "Boolean",
  "iMessageAndFaceTimeScreenDisabled": "Boolean",
  "onBoardingScreenDisabled": "Boolean",
  "simSetupScreenDisabled": "Boolean",
  "softwareUpdateScreenDisabled": "Boolean",
  "watchMigrationScreenDisabled": "Boolean",
  "appearanceScreenDisabled": "Boolean",
  "expressLanguageScreenDisabled": "Boolean",
  "preferredLanguageScreenDisabled": "Boolean",
  "deviceToDeviceMigrationDisabled": "Boolean",
  "welcomeScreenDisabled": "Boolean",
  "passCodeDisabled": "Boolean",
  "zoomDisabled": "Boolean",
  "restoreCompletedScreenDisabled": "Boolean",
  "updateCompleteScreenDisabled": "Boolean"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.depIOSEnrollmentProfile"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.depIOSEnrollmentProfile",
  "id": "a0eaf3bc-f3bc-a0ea-bcf3-eaa0bcf3eaa0",
  "displayName": "String",
  "description": "String",
  "requiresUserAuthentication": "Boolean",
  "configurationEndpointUrl": "String",
  "enableAuthenticationViaCompanyPortal": "Boolean",
  "requireCompanyPortalOnSetupAssistantEnrolledDevices": "Boolean",
  "isDefault": "Boolean",
  "supervisedModeEnabled": "Boolean",
  "supportDepartment": "String",
  "isMandatory": "Boolean",
  "locationDisabled": "Boolean",
  "supportPhoneNumber": "String",
  "profileRemovalDisabled": "Boolean",
  "restoreBlocked": "Boolean",
  "appleIdDisabled": "Boolean",
  "termsAndConditionsDisabled": "Boolean",
  "touchIdDisabled": "Boolean",
  "applePayDisabled": "Boolean",
  "siriDisabled": "Boolean",
  "diagnosticsDisabled": "Boolean",
  "displayToneSetupDisabled": "Boolean",
  "privacyPaneDisabled": "Boolean",
  "screenTimeScreenDisabled": "Boolean",
  "deviceNameTemplate": "String",
  "configurationWebUrl": "Boolean",
  "iTunesPairingMode": "String",
  "managementCertificates": [
    {
      "@odata.type": "microsoft.graph.managementCertificateWithThumbprint"
    }
  ],
  "restoreFromAndroidDisabled": "Boolean",
  "awaitDeviceConfiguredConfirmation": "Boolean",
  "sharedIPadMaximumUserCount": "Integer",
  "enableSharedIPad": "Boolean",
  "companyPortalVppTokenId": "String",
  "enableSingleAppEnrollmentMode": "Boolean",
  "homeButtonScreenDisabled": "Boolean",
  "iMessageAndFaceTimeScreenDisabled": "Boolean",
  "onBoardingScreenDisabled": "Boolean",
  "simSetupScreenDisabled": "Boolean",
  "softwareUpdateScreenDisabled": "Boolean",
  "watchMigrationScreenDisabled": "Boolean",
  "appearanceScreenDisabled": "Boolean",
  "expressLanguageScreenDisabled": "Boolean",
  "preferredLanguageScreenDisabled": "Boolean",
  "deviceToDeviceMigrationDisabled": "Boolean",
  "welcomeScreenDisabled": "Boolean",
  "passCodeDisabled": "Boolean",
  "zoomDisabled": "Boolean",
  "restoreCompletedScreenDisabled": "Boolean",
  "updateCompleteScreenDisabled": "Boolean"
}
```

