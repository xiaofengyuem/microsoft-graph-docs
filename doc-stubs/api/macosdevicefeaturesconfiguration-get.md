---
title: "Get macOSDeviceFeaturesConfiguration"
description: "Read the properties and relationships of a macOSDeviceFeaturesConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get macOSDeviceFeaturesConfiguration
Namespace: microsoft.graph

Read the properties and relationships of a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.

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
GET ** Entity URI for microsoft.graph.macOSDeviceFeaturesConfiguration not found
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

If successful, this method returns a `200 OK` response code and a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_macosdevicefeaturesconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Entity URI for microsoft.graph.macOSDeviceFeaturesConfiguration not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.macOSDeviceFeaturesConfiguration"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.macOSDeviceFeaturesConfiguration",
    "id": "f9e32581-2581-f9e3-8125-e3f98125e3f9",
    "lastModifiedDateTime": "String (timestamp)",
    "roleScopeTagIds": [
      "String"
    ],
    "supportsScopeTags": "Boolean",
    "deviceManagementApplicabilityRuleOsEdition": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
    },
    "deviceManagementApplicabilityRuleOsVersion": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
    },
    "deviceManagementApplicabilityRuleDeviceMode": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
    },
    "createdDateTime": "String (timestamp)",
    "description": "String",
    "displayName": "String",
    "version": "Integer",
    "airPrintDestinations": [
      {
        "@odata.type": "microsoft.graph.airPrintDestination"
      }
    ],
    "autoLaunchItems": [
      {
        "@odata.type": "microsoft.graph.macOSLaunchItem"
      }
    ],
    "adminShowHostInfo": "Boolean",
    "loginWindowText": "String",
    "authorizedUsersListHidden": "Boolean",
    "authorizedUsersListHideLocalUsers": "Boolean",
    "authorizedUsersListHideMobileAccounts": "Boolean",
    "authorizedUsersListIncludeNetworkUsers": "Boolean",
    "authorizedUsersListHideAdminUsers": "Boolean",
    "authorizedUsersListShowOtherManagedUsers": "Boolean",
    "shutDownDisabled": "Boolean",
    "restartDisabled": "Boolean",
    "sleepDisabled": "Boolean",
    "consoleAccessDisabled": "Boolean",
    "shutDownDisabledWhileLoggedIn": "Boolean",
    "restartDisabledWhileLoggedIn": "Boolean",
    "powerOffDisabledWhileLoggedIn": "Boolean",
    "logOutDisabledWhileLoggedIn": "Boolean",
    "screenLockDisableImmediate": "Boolean",
    "associatedDomains": [
      {
        "@odata.type": "microsoft.graph.keyValuePair"
      }
    ],
    "appAssociatedDomains": [
      {
        "@odata.type": "microsoft.graph.macOSAssociatedDomainsItem"
      }
    ],
    "singleSignOnExtension": {
      "@odata.type": "microsoft.graph.singleSignOnExtension"
    },
    "macOSSingleSignOnExtension": {
      "@odata.type": "microsoft.graph.macOSSingleSignOnExtension"
    },
    "contentCachingEnabled": "Boolean",
    "contentCachingType": "String",
    "contentCachingMaxSizeBytes": "Integer",
    "contentCachingDataPath": "String",
    "contentCachingDisableConnectionSharing": "Boolean",
    "contentCachingForceConnectionSharing": "Boolean",
    "contentCachingClientPolicy": "String",
    "contentCachingClientListenRanges": [
      {
        "@odata.type": "microsoft.graph.iPv4CidrRange"
      }
    ],
    "contentCachingPeerPolicy": "String",
    "contentCachingPeerListenRanges": [
      {
        "@odata.type": "microsoft.graph.iPv4CidrRange"
      }
    ],
    "contentCachingPeerFilterRanges": [
      {
        "@odata.type": "microsoft.graph.iPv4CidrRange"
      }
    ],
    "contentCachingParentSelectionPolicy": "String",
    "contentCachingParents": [
      "String"
    ],
    "contentCachingLogClientIdentities": "Boolean",
    "contentCachingPublicRanges": [
      {
        "@odata.type": "microsoft.graph.iPv4CidrRange"
      }
    ],
    "contentCachingBlockDeletion": "Boolean",
    "contentCachingShowAlerts": "Boolean",
    "contentCachingKeepAwake": "Boolean",
    "contentCachingPort": "Integer"
  }
}
```

