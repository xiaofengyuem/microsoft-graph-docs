---
title: "deviceManagementReports resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagementReports resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List reports](../api/intune-devicemanagement-list-reports.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md) collection|Get the deviceManagementReports resources from the reports navigation property.|
|[Create reports](../api/intune-devicemanagement-post-reports.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Create a new deviceManagementReports object.|
|[Update reports](../api/intune-devicemanagement-update-reports.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Update the properties of a reports object.|
|[Get reports](../api/intune-devicemanagement-get-devicemanagementreports.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Read the properties and relationships of a [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[Delete reports](../api/intune-devicemanagement-delete-reports.md)|None|Delete a [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[List deviceManagementReports](../api/intune-devicemanagementreports-list.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md) collection|Get a list of the [deviceManagementReports](../resources/devicemanagementreports.md) objects and their properties.|
|[Create deviceManagementReports](../api/intune-devicemanagementreports-create.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Create a new [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[Get deviceManagementReports](../api/intune-devicemanagementreports-get.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Read the properties and relationships of a [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[Update deviceManagementReports](../api/intune-devicemanagementreports-update.md)|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|Update the properties of a [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[Delete deviceManagementReports](../api/intune-devicemanagementreports-delete.md)|None|Deletes a [deviceManagementReports](../resources/intune-devicemanagementreports.md) object.|
|[getActiveMalwareSummaryReport](../api/intune-devicemanagementreports-getactivemalwaresummaryreport.md)|Stream|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|cachedReportConfigurations|[deviceManagementCachedReportConfiguration](../resources/intune-devicemanagementcachedreportconfiguration.md) collection|**TODO: Add Description**|
|exportJobs|[deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) collection|**TODO: Add Description**|
|reportSchedules|[deviceManagementReportSchedule](../resources/intune-devicemanagementreportschedule.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementReports",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementReports"
}
```

