---
title: "macOSDeviceFeaturesConfiguration resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# macOSDeviceFeaturesConfiguration resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [appleDeviceFeaturesConfigurationBase](../resources/appledevicefeaturesconfigurationbase.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List macOSDeviceFeaturesConfigurations](../api/macosdevicefeaturesconfiguration-list.md)|[macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) collection|Get a list of the [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) objects and their properties.|
|[Create macOSDeviceFeaturesConfiguration](../api/macosdevicefeaturesconfiguration-create.md)|[macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md)|Create a new [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.|
|[Get macOSDeviceFeaturesConfiguration](../api/macosdevicefeaturesconfiguration-get.md)|[macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md)|Read the properties and relationships of a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.|
|[Update macOSDeviceFeaturesConfiguration](../api/macosdevicefeaturesconfiguration-update.md)|[macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md)|Update the properties of a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.|
|[Delete macOSDeviceFeaturesConfiguration](../api/macosdevicefeaturesconfiguration-delete.md)|None|Deletes a [macOSDeviceFeaturesConfiguration](../resources/macosdevicefeaturesconfiguration.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|adminShowHostInfo|Boolean|**TODO: Add Description**|
|airPrintDestinations|[airPrintDestination](../resources/intune-airprintdestination.md) collection|**TODO: Add Description** Inherited from [appleDeviceFeaturesConfigurationBase](../resources/appledevicefeaturesconfigurationbase.md)|
|appAssociatedDomains|[macOSAssociatedDomainsItem](../resources/intune-macosassociateddomainsitem.md) collection|**TODO: Add Description**|
|associatedDomains|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|authorizedUsersListHidden|Boolean|**TODO: Add Description**|
|authorizedUsersListHideAdminUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListHideLocalUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListHideMobileAccounts|Boolean|**TODO: Add Description**|
|authorizedUsersListIncludeNetworkUsers|Boolean|**TODO: Add Description**|
|authorizedUsersListShowOtherManagedUsers|Boolean|**TODO: Add Description**|
|autoLaunchItems|[macOSLaunchItem](../resources/intune-macoslaunchitem.md) collection|**TODO: Add Description**|
|consoleAccessDisabled|Boolean|**TODO: Add Description**|
|contentCachingBlockDeletion|Boolean|**TODO: Add Description**|
|contentCachingClientListenRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingClientPolicy|macOSContentCachingClientPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `clientsInLocalNetwork`, `clientsWithSamePublicIpAddress`, `clientsInCustomLocalNetworks`, `clientsInCustomLocalNetworksWithFallback`.|
|contentCachingDataPath|String|**TODO: Add Description**|
|contentCachingDisableConnectionSharing|Boolean|**TODO: Add Description**|
|contentCachingEnabled|Boolean|**TODO: Add Description**|
|contentCachingForceConnectionSharing|Boolean|**TODO: Add Description**|
|contentCachingKeepAwake|Boolean|**TODO: Add Description**|
|contentCachingLogClientIdentities|Boolean|**TODO: Add Description**|
|contentCachingMaxSizeBytes|Int32|**TODO: Add Description**|
|contentCachingParents|String collection|**TODO: Add Description**|
|contentCachingParentSelectionPolicy|macOSContentCachingParentSelectionPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `roundRobin`, `firstAvailable`, `urlPathHash`, `random`, `stickyAvailable`.|
|contentCachingPeerFilterRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingPeerListenRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingPeerPolicy|macOSContentCachingPeerPolicy|**TODO: Add Description**. Possible values are: `notConfigured`, `peersInLocalNetwork`, `peersWithSamePublicIpAddress`, `peersInCustomLocalNetworks`.|
|contentCachingPort|Int32|**TODO: Add Description**|
|contentCachingPublicRanges|[ipRange](../resources/intune-iprange.md) collection|**TODO: Add Description**|
|contentCachingShowAlerts|Boolean|**TODO: Add Description**|
|contentCachingType|macOSContentCachingType|**TODO: Add Description**. Possible values are: `notConfigured`, `userContentOnly`, `sharedContentOnly`.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|description|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleDeviceMode|[deviceManagementApplicabilityRuleDeviceMode](../resources/intune-devicemanagementapplicabilityruledevicemode.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsEdition|[deviceManagementApplicabilityRuleOsEdition](../resources/intune-devicemanagementapplicabilityruleosedition.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsVersion|[deviceManagementApplicabilityRuleOsVersion](../resources/intune-devicemanagementapplicabilityruleosversion.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|loginWindowText|String|**TODO: Add Description**|
|logOutDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|macOSSingleSignOnExtension|[macOSSingleSignOnExtension](../resources/intune-macossinglesignonextension.md)|**TODO: Add Description**|
|powerOffDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|restartDisabled|Boolean|**TODO: Add Description**|
|restartDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|screenLockDisableImmediate|Boolean|**TODO: Add Description**|
|shutDownDisabled|Boolean|**TODO: Add Description**|
|shutDownDisabledWhileLoggedIn|Boolean|**TODO: Add Description**|
|singleSignOnExtension|[singleSignOnExtension](../resources/intune-singlesignonextension.md)|**TODO: Add Description**|
|sleepDisabled|Boolean|**TODO: Add Description**|
|supportsScopeTags|Boolean|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|version|Int32|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|assignments|[deviceConfigurationAssignment](../resources/intune-deviceconfigurationassignment.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune-settingstatedevicesummary.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune-deviceconfigurationdevicestatus.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|deviceStatusOverview|[deviceConfigurationDeviceOverview](../resources/intune-deviceconfigurationdeviceoverview.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune-deviceconfigurationgroupassignment.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|singleSignOnExtensionPkinitCertificate|[macOSCertificateProfileBase](../resources/macoscertificateprofilebase.md)|**TODO: Add Description**|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune-deviceconfigurationuserstatus.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|userStatusOverview|[deviceConfigurationUserOverview](../resources/intune-deviceconfigurationuseroverview.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.macOSDeviceFeaturesConfiguration",
  "baseType": "microsoft.graph.appleDeviceFeaturesConfigurationBase",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSDeviceFeaturesConfiguration",
  "id": "String (identifier)",
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

