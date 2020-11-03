---
title: "Create macOSDeviceFeaturesConfiguration"
description: "Create a new macOSDeviceFeaturesConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create macOSDeviceFeaturesConfiguration
Namespace: microsoft.graph

Create a new [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.

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
POST ** Collection URI for microsoft.graph.macOSDeviceFeaturesConfiguration not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.

The following table shows the properties that are required when you create the [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|supportsScopeTags|Boolean|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsEdition|[deviceManagementApplicabilityRuleOsEdition](../resources/intune-devicemanagementapplicabilityruleosedition.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsVersion|[deviceManagementApplicabilityRuleOsVersion](../resources/intune-devicemanagementapplicabilityruleosversion.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleDeviceMode|[deviceManagementApplicabilityRuleDeviceMode](../resources/intune-devicemanagementapplicabilityruledevicemode.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|description|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|version|Int32|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|airPrintDestinations|[airPrintDestination](../resources/intune-airprintdestination.md) collection|**TODO: Add Description** Inherited from [appleDeviceFeaturesConfigurationBase](../resources/appledevicefeaturesconfigurationbase.md)|
|autoLaunchItems|[macOSLaunchItem](../resources/intune-macoslaunchitem.md) collection|**TODO: Add Description**|
|adminShowHostInfo|Boolean|**TODO: Add Description**|
|loginWindowText|String|**TODO: Add Description**|
|authorizedUsersListHidden|Boolean|**TODO: Add Description**|
|authorizedUsersListHideLocalUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListHideMobileAccounts|Boolean|**TODO: Add Description**|
|authorizedUsersListIncludeNetworkUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListHideAdminUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListShowOtherManagedUsers|Boolean|**TODO: Add Description**|
|shutDownDisabled|Boolean|**TODO: Add Description**|
|restartDisabled|Boolean|**TODO: Add Description**|
|sleepDisabled|Boolean|**TODO: Add Description**|
|consoleAccessDisabled|Boolean|**TODO: Add Description**|
|shutDownDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|restartDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|powerOffDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|logOutDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|screenLockDisableImmediate|Boolean|**TODO: Add Description**|
|associatedDomains|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|appAssociatedDomains|[macOSAssociatedDomainsItem](../resources/intune-macosassociateddomainsitem.md) collection|**TODO: Add Description**|
|singleSignOnExtension|[singleSignOnExtension](../resources/intune-singlesignonextension.md)|**TODO: Add Description**|
|macOSSingleSignOnExtension|[macOSSingleSignOnExtension](../resources/intune-macossinglesignonextension.md)|**TODO: Add Description**|
|contentCachingEnabled|Boolean|**TODO: Add Description**|
|contentCachingType|macOSContentCachingType|**TODO: Add Description**. Possible values are: `notConfigured`, `userContentOnly`, `sharedContentOnly`.|
|contentCachingMaxSizeBytes|Int32|**TODO: Add Description**|
|contentCachingDataPath|String|**TODO: Add Description**|
|contentCachingDisableConnectionSharing|Boolean|**TODO: Add Description**|
|contentCachingForceConnectionSharing|Boolean|**TODO: Add Description**|
|contentCachingClientPolicy|macOSContentCachingClientPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `clientsInLocalNetwork`, `clientsWithSamePublicIpAddress`, `clientsInCustomLocalNetworks`, `clientsInCustomLocalNetworksWithFallback`.|
|contentCachingClientListenRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingPeerPolicy|macOSContentCachingPeerPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `peersInLocalNetwork`, `peersWithSamePublicIpAddress`, `peersInCustomLocalNetworks`.|
|contentCachingPeerListenRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingPeerFilterRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingParentSelectionPolicy|macOSContentCachingParentSelectionPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `roundRobin`, `firstAvailable`, `urlPathHash`, `random`, `stickyAvailable`.|
|contentCachingParents|String collection|**TODO: Add Description**|
|contentCachingLogClientIdentities|Boolean|**TODO: Add Description**|
|contentCachingPublicRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingBlockDeletion|Boolean|**TODO: Add Description**|
|contentCachingShowAlerts|Boolean|**TODO: Add Description**|
|contentCachingKeepAwake|Boolean|**TODO: Add Description**|
|contentCachingPort|Int32|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_macosdevicefeaturesconfiguration_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.macOSDeviceFeaturesConfiguration not found
Content-Type: application/json
Content-length: 3141

{
  "@odata.type": "#microsoft.graph.macOSDeviceFeaturesConfiguration",
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
HTTP/1.1 201 Created

Content-Type: application/json
{
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
```

