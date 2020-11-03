---
title: "List depIOSEnrollmentProfiles"
description: "Get a list of the depIOSEnrollmentProfile objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List depIOSEnrollmentProfiles
Namespace: microsoft.graph

Get a list of the [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md) objects and their properties.

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
GET ** Collection URI for microsoft.graph.depIOSEnrollmentProfile not found
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

If successful, this method returns a `200 OK` response code and a collection of [depIOSEnrollmentProfile](../resources/depiosenrollmentprofile.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_depiosenrollmentprofile"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for microsoft.graph.depIOSEnrollmentProfile not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.depIOSEnrollmentProfile)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
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
  ]
}
```

