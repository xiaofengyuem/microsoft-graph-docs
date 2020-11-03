---
title: "iosCompliancePolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# iosCompliancePolicy resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List iosCompliancePolicies](../api/ioscompliancepolicy-list.md)|[iosCompliancePolicy](../resources/ioscompliancepolicy.md) collection|Get a list of the [iosCompliancePolicy](../resources/ioscompliancepolicy.md) objects and their properties.|
|[Create iosCompliancePolicy](../api/ioscompliancepolicy-create.md)|[iosCompliancePolicy](../resources/ioscompliancepolicy.md)|Create a new [iosCompliancePolicy](../resources/ioscompliancepolicy.md) object.|
|[Get iosCompliancePolicy](../api/ioscompliancepolicy-get.md)|[iosCompliancePolicy](../resources/ioscompliancepolicy.md)|Read the properties and relationships of an [iosCompliancePolicy](../resources/ioscompliancepolicy.md) object.|
|[Update iosCompliancePolicy](../api/ioscompliancepolicy-update.md)|[iosCompliancePolicy](../resources/ioscompliancepolicy.md)|Update the properties of an [iosCompliancePolicy](../resources/ioscompliancepolicy.md) object.|
|[Delete iosCompliancePolicy](../api/ioscompliancepolicy-delete.md)|None|Deletes an [iosCompliancePolicy](../resources/ioscompliancepolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|advancedThreatProtectionRequiredSecurityLevel|deviceThreatProtectionLevel|**TODO: Add Description**. Possible values are: `unavailable`, `secured`, `low`, `medium`, `high`, `notSet`.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|
|description|String|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|
|deviceThreatProtectionEnabled|Boolean|**TODO: Add Description**|
|deviceThreatProtectionRequiredSecurityLevel|deviceThreatProtectionLevel|**TODO: Add Description**. Possible values are: `unavailable`, `secured`, `low`, `medium`, `high`, `notSet`.|
|displayName|String|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|
|managedEmailProfileRequired|Boolean|**TODO: Add Description**|
|osMaximumBuildVersion|String|**TODO: Add Description**|
|osMaximumVersion|String|**TODO: Add Description**|
|osMinimumBuildVersion|String|**TODO: Add Description**|
|osMinimumVersion|String|**TODO: Add Description**|
|passcodeBlockSimple|Boolean|**TODO: Add Description**|
|passcodeExpirationDays|Int32|**TODO: Add Description**|
|passcodeMinimumCharacterSetCount|Int32|**TODO: Add Description**|
|passcodeMinimumLength|Int32|**TODO: Add Description**|
|passcodeMinutesOfInactivityBeforeLock|Int32|**TODO: Add Description**|
|passcodeMinutesOfInactivityBeforeScreenTimeout|Int32|**TODO: Add Description**|
|passcodePreviousPasscodeBlockCount|Int32|**TODO: Add Description**|
|passcodeRequired|Boolean|**TODO: Add Description**|
|passcodeRequiredType|requiredPasswordType|**TODO: Add Description**. Possible values are: `deviceDefault`, `alphanumeric`, `numeric`.|
|restrictedApps|[appListItem](../resources/intune-applistitem.md) collection|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|
|securityBlockJailbrokenDevices|Boolean|**TODO: Add Description**|
|version|Int32|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|assignments|[deviceCompliancePolicyAssignment](../resources/intune-devicecompliancepolicyassignment.md) collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune-settingstatedevicesummary.md) collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|deviceStatuses|[deviceComplianceDeviceStatus](../resources/intune-devicecompliancedevicestatus.md) collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|deviceStatusOverview|[deviceComplianceDeviceOverview](../resources/intune-devicecompliancedeviceoverview.md)|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|scheduledActionsForRule|[deviceComplianceScheduledActionForRule](../resources/intune-devicecompliancescheduledactionforrule.md) collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|userStatuses|[deviceComplianceUserStatus](../resources/intune-devicecomplianceuserstatus.md) collection|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|
|userStatusOverview|[deviceComplianceUserOverview](../resources/intune-devicecomplianceuseroverview.md)|**TODO: Add Description** Inherited from [deviceCompliancePolicy](../resources/devicecompliancepolicy.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.iosCompliancePolicy",
  "baseType": "microsoft.graph.deviceCompliancePolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.iosCompliancePolicy",
  "id": "String (identifier)",
  "roleScopeTagIds": [
    "String"
  ],
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "lastModifiedDateTime": "String (timestamp)",
  "displayName": "String",
  "version": "Integer",
  "passcodeBlockSimple": "Boolean",
  "passcodeExpirationDays": "Integer",
  "passcodeMinimumLength": "Integer",
  "passcodeMinutesOfInactivityBeforeLock": "Integer",
  "passcodeMinutesOfInactivityBeforeScreenTimeout": "Integer",
  "passcodePreviousPasscodeBlockCount": "Integer",
  "passcodeMinimumCharacterSetCount": "Integer",
  "passcodeRequiredType": "String",
  "passcodeRequired": "Boolean",
  "osMinimumVersion": "String",
  "osMaximumVersion": "String",
  "osMinimumBuildVersion": "String",
  "osMaximumBuildVersion": "String",
  "securityBlockJailbrokenDevices": "Boolean",
  "deviceThreatProtectionEnabled": "Boolean",
  "deviceThreatProtectionRequiredSecurityLevel": "String",
  "advancedThreatProtectionRequiredSecurityLevel": "String",
  "managedEmailProfileRequired": "Boolean",
  "restrictedApps": [
    {
      "@odata.type": "microsoft.graph.appListItem"
    }
  ]
}
```

