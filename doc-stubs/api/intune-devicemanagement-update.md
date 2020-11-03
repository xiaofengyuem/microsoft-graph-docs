---
title: "Update deviceManagement"
description: "Update the properties of a deviceManagement object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update deviceManagement
Namespace: microsoft.graph

Update the properties of a [deviceManagement](../resources/intune-devicemanagement.md) object.

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
PATCH /deviceManagement
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [deviceManagement](../resources/intune-devicemanagement.md) object.

The following table shows the properties that are required when you create the [deviceManagement](../resources/intune-devicemanagement.md).

|Property|Type|Description|
|:---|:---|:---|
|settings|[deviceManagementSettings](../resources/intune-devicemanagementsettings.md)|**TODO: Add Description**|
|maximumDepTokens|Int32|**TODO: Add Description**|
|intuneAccountId|Guid|**TODO: Add Description**|
|lastReportAggregationDateTime|DateTimeOffset|**TODO: Add Description**|
|deviceComplianceReportSummarizationDateTime|DateTimeOffset|**TODO: Add Description**|
|legacyPcManangementEnabled|Boolean|**TODO: Add Description**|
|unlicensedAdminstratorsEnabled|Boolean|**TODO: Add Description**|
|intuneBrand|[intuneBrand](../resources/intune-intunebrand.md)|**TODO: Add Description**|
|subscriptionState|deviceManagementSubscriptionState|**TODO: Add Description**. Possible values are: `pending`, `active`, `warning`, `disabled`, `deleted`, `blocked`, `lockedOut`.|
|subscriptions|deviceManagementSubscriptions|**TODO: Add Description**. Possible values are: `none`, `intune`, `office365`, `intunePremium`, `intune_EDU`, `intune_SMB`.|
|managedDeviceCleanupSettings|[managedDeviceCleanupSettings](../resources/intune-manageddevicecleanupsettings.md)|**TODO: Add Description**|
|adminConsent|[adminConsent](../resources/intune-adminconsent.md)|**TODO: Add Description**|
|deviceProtectionOverview|[deviceProtectionOverview](../resources/intune-deviceprotectionoverview.md)|**TODO: Add Description**|
|windowsMalwareOverview|[windowsMalwareOverview](../resources/intune-windowsmalwareoverview.md)|**TODO: Add Description**|
|accountMoveCompletionDateTime|DateTimeOffset|**TODO: Add Description**|
|userExperienceAnalyticsSettings|[userExperienceAnalyticsSettings](../resources/intune-userexperienceanalyticssettings.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [deviceManagement](../resources/intune-devicemanagement.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_devicemanagement"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceManagement
Content-Type: application/json
Content-length: 1132

{
  "@odata.type": "#microsoft.graph.deviceManagement",
  "settings": {
    "@odata.type": "microsoft.graph.deviceManagementSettings"
  },
  "maximumDepTokens": "Integer",
  "intuneAccountId": "Guid",
  "lastReportAggregationDateTime": "String (timestamp)",
  "deviceComplianceReportSummarizationDateTime": "String (timestamp)",
  "legacyPcManangementEnabled": "Boolean",
  "unlicensedAdminstratorsEnabled": "Boolean",
  "intuneBrand": {
    "@odata.type": "microsoft.graph.intuneBrand"
  },
  "subscriptionState": "String",
  "subscriptions": "String",
  "managedDeviceCleanupSettings": {
    "@odata.type": "microsoft.graph.managedDeviceCleanupSettings"
  },
  "adminConsent": {
    "@odata.type": "microsoft.graph.adminConsent"
  },
  "deviceProtectionOverview": {
    "@odata.type": "microsoft.graph.deviceProtectionOverview"
  },
  "windowsMalwareOverview": {
    "@odata.type": "microsoft.graph.windowsMalwareOverview"
  },
  "accountMoveCompletionDateTime": "String (timestamp)",
  "userExperienceAnalyticsSettings": {
    "@odata.type": "microsoft.graph.userExperienceAnalyticsSettings"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.deviceManagement",
  "settings": {
    "@odata.type": "microsoft.graph.deviceManagementSettings"
  },
  "maximumDepTokens": "Integer",
  "intuneAccountId": "Guid",
  "lastReportAggregationDateTime": "String (timestamp)",
  "deviceComplianceReportSummarizationDateTime": "String (timestamp)",
  "legacyPcManangementEnabled": "Boolean",
  "unlicensedAdminstratorsEnabled": "Boolean",
  "intuneBrand": {
    "@odata.type": "microsoft.graph.intuneBrand"
  },
  "subscriptionState": "String",
  "subscriptions": "String",
  "managedDeviceCleanupSettings": {
    "@odata.type": "microsoft.graph.managedDeviceCleanupSettings"
  },
  "adminConsent": {
    "@odata.type": "microsoft.graph.adminConsent"
  },
  "deviceProtectionOverview": {
    "@odata.type": "microsoft.graph.deviceProtectionOverview"
  },
  "windowsMalwareOverview": {
    "@odata.type": "microsoft.graph.windowsMalwareOverview"
  },
  "accountMoveCompletionDateTime": "String (timestamp)",
  "userExperienceAnalyticsSettings": {
    "@odata.type": "microsoft.graph.userExperienceAnalyticsSettings"
  }
}
```

