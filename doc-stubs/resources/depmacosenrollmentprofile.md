---
title: "depMacOSEnrollmentProfile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# depMacOSEnrollmentProfile resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List defaultMacOsEnrollmentProfile](../api/intune-deponboardingsetting-list-defaultmacosenrollmentprofile.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) collection|Get the depMacOSEnrollmentProfile resources from the defaultMacOsEnrollmentProfile navigation property.|
|[Add defaultMacOsEnrollmentProfile](../api/intune-deponboardingsetting-post-defaultmacosenrollmentprofile.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md)|Add defaultMacOsEnrollmentProfile by posting to the defaultMacOsEnrollmentProfile collection.|
|[Remove defaultMacOsEnrollmentProfile](../api/intune-deponboardingsetting-delete-defaultmacosenrollmentprofile.md)|None|Remove a [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) object.|
|[List depMacOSEnrollmentProfiles](../api/depmacosenrollmentprofile-list.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) collection|Get a list of the [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) objects and their properties.|
|[Create depMacOSEnrollmentProfile](../api/depmacosenrollmentprofile-create.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md)|Create a new [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) object.|
|[Get depMacOSEnrollmentProfile](../api/depmacosenrollmentprofile-get.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md)|Read the properties and relationships of a [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) object.|
|[Update depMacOSEnrollmentProfile](../api/depmacosenrollmentprofile-update.md)|[depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md)|Update the properties of a [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) object.|
|[Delete depMacOSEnrollmentProfile](../api/depmacosenrollmentprofile-delete.md)|None|Deletes a [depMacOSEnrollmentProfile](../resources/depmacosenrollmentprofile.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|accessibilityScreenDisabled|Boolean|**TODO: Add Description**|
|appleIdDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|applePayDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|chooseYourLockScreenDisabled|Boolean|**TODO: Add Description**|
|configurationEndpointUrl|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|configurationWebUrl|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|description|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|deviceNameTemplate|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|diagnosticsDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|displayName|String|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|displayToneSetupDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|enableAuthenticationViaCompanyPortal|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|fileVaultDisabled|Boolean|**TODO: Add Description**|
|iCloudDiagnosticsDisabled|Boolean|**TODO: Add Description**|
|iCloudStorageDisabled|Boolean|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|isDefault|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|isMandatory|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|locationDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|passCodeDisabled|Boolean|**TODO: Add Description**|
|privacyPaneDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|profileRemovalDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|registrationDisabled|Boolean|**TODO: Add Description**|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|requiresUserAuthentication|Boolean|**TODO: Add Description** Inherited from [enrollmentProfile](../resources/intune-enrollmentprofile.md)|
|restoreBlocked|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|screenTimeScreenDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|siriDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supervisedModeEnabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supportDepartment|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|supportPhoneNumber|String|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|termsAndConditionsDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|touchIdDisabled|Boolean|**TODO: Add Description** Inherited from [depEnrollmentBaseProfile](../resources/depenrollmentbaseprofile.md)|
|zoomDisabled|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.depMacOSEnrollmentProfile",
  "baseType": "microsoft.graph.depEnrollmentBaseProfile",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.depMacOSEnrollmentProfile",
  "id": "String (identifier)",
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
  "registrationDisabled": "Boolean",
  "fileVaultDisabled": "Boolean",
  "iCloudDiagnosticsDisabled": "Boolean",
  "passCodeDisabled": "Boolean",
  "zoomDisabled": "Boolean",
  "iCloudStorageDisabled": "Boolean",
  "chooseYourLockScreenDisabled": "Boolean",
  "accessibilityScreenDisabled": "Boolean"
}
```

