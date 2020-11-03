---
title: "androidDeviceOwnerVpnConfiguration resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# androidDeviceOwnerVpnConfiguration resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [vpnConfiguration](../resources/vpnconfiguration.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List androidDeviceOwnerVpnConfigurations](../api/androiddeviceownervpnconfiguration-list.md)|[androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) collection|Get a list of the [androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) objects and their properties.|
|[Create androidDeviceOwnerVpnConfiguration](../api/androiddeviceownervpnconfiguration-create.md)|[androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md)|Create a new [androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) object.|
|[Get androidDeviceOwnerVpnConfiguration](../api/androiddeviceownervpnconfiguration-get.md)|[androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md)|Read the properties and relationships of an [androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) object.|
|[Update androidDeviceOwnerVpnConfiguration](../api/androiddeviceownervpnconfiguration-update.md)|[androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md)|Update the properties of an [androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) object.|
|[Delete androidDeviceOwnerVpnConfiguration](../api/androiddeviceownervpnconfiguration-delete.md)|None|Deletes an [androidDeviceOwnerVpnConfiguration](../resources/androiddeviceownervpnconfiguration.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|alwaysOn|Boolean|**TODO: Add Description**|
|alwaysOnLockdown|Boolean|**TODO: Add Description**|
|authenticationMethod|vpnAuthenticationMethod|**TODO: Add Description** Inherited from [vpnConfiguration](../resources/vpnconfiguration.md). Possible values are: `certificate`, `usernameAndPassword`, `sharedSecret`, `derivedCredential`, `azureAD`.|
|connectionName|String|**TODO: Add Description** Inherited from [vpnConfiguration](../resources/vpnconfiguration.md)|
|connectionType|androidVpnConnectionType|**TODO: Add Description**. Possible values are: `ciscoAnyConnect`, `pulseSecure`, `f5EdgeClient`, `dellSonicWallMobileConnect`, `checkPointCapsuleVpn`, `citrix`, `microsoftTunnel`, `netMotionMobility`.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|customData|[keyValue](../resources/intune-keyvalue.md) collection|**TODO: Add Description**|
|customKeyValueData|[keyValuePair](../resources/synchronization-keyvaluepair.md) collection|**TODO: Add Description**|
|description|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleDeviceMode|[deviceManagementApplicabilityRuleDeviceMode](../resources/intune-devicemanagementapplicabilityruledevicemode.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsEdition|[deviceManagementApplicabilityRuleOsEdition](../resources/intune-devicemanagementapplicabilityruleosedition.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsVersion|[deviceManagementApplicabilityRuleOsVersion](../resources/intune-devicemanagementapplicabilityruleosversion.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|microsoftTunnelSiteId|String|**TODO: Add Description**|
|proxyServer|[vpnProxyServer](../resources/intune-vpnproxyserver.md)|**TODO: Add Description**|
|realm|String|**TODO: Add Description** Inherited from [vpnConfiguration](../resources/vpnconfiguration.md)|
|role|String|**TODO: Add Description** Inherited from [vpnConfiguration](../resources/vpnconfiguration.md)|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|servers|[vpnServer](../resources/intune-vpnserver.md) collection|**TODO: Add Description** Inherited from [vpnConfiguration](../resources/vpnconfiguration.md)|
|supportsScopeTags|Boolean|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|targetedMobileApps|[appListItem](../resources/intune-applistitem.md) collection|**TODO: Add Description**|
|targetedPackageIds|String collection|**TODO: Add Description**|
|version|Int32|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|assignments|[deviceConfigurationAssignment](../resources/intune-deviceconfigurationassignment.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|derivedCredentialSettings|[deviceManagementDerivedCredentialSettings](../resources/intune-devicemanagementderivedcredentialsettings.md)|**TODO: Add Description**|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune-settingstatedevicesummary.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune-deviceconfigurationdevicestatus.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|deviceStatusOverview|[deviceConfigurationDeviceOverview](../resources/intune-deviceconfigurationdeviceoverview.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune-deviceconfigurationgroupassignment.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|identityCertificate|[androidDeviceOwnerCertificateProfileBase](../resources/androiddeviceownercertificateprofilebase.md)|**TODO: Add Description**|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune-deviceconfigurationuserstatus.md) collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|
|userStatusOverview|[deviceConfigurationUserOverview](../resources/intune-deviceconfigurationuseroverview.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/deviceconfiguration.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.androidDeviceOwnerVpnConfiguration",
  "baseType": "microsoft.graph.vpnConfiguration",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.androidDeviceOwnerVpnConfiguration",
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
  "authenticationMethod": "String",
  "connectionName": "String",
  "role": "String",
  "realm": "String",
  "servers": [
    {
      "@odata.type": "microsoft.graph.vpnServer"
    }
  ],
  "connectionType": "String",
  "proxyServer": {
    "@odata.type": "microsoft.graph.vpnProxyServer"
  },
  "targetedPackageIds": [
    "String"
  ],
  "targetedMobileApps": [
    {
      "@odata.type": "microsoft.graph.appListItem"
    }
  ],
  "alwaysOn": "Boolean",
  "alwaysOnLockdown": "Boolean",
  "microsoftTunnelSiteId": "String",
  "customData": [
    {
      "@odata.type": "microsoft.graph.keyValue"
    }
  ],
  "customKeyValueData": [
    {
      "@odata.type": "microsoft.graph.keyValuePair"
    }
  ]
}
```

