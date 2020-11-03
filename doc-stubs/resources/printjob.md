---
title: "printJob resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# printJob resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List jobs](../api/printer-list-jobs.md)|[printJob](../resources/printjob.md) collection|Get the printJob resources from the jobs navigation property.|
|[Create jobs](../api/printer-post-jobs.md)|[printJob](../resources/printjob.md)|Create a new printJob object.|
|[Update jobs](../api/printer-update-jobs.md)|[printJob](../resources/printjob.md)|Update the properties of a jobs object.|
|[Get jobs](../api/printer-get-printjob.md)|[printJob](../resources/printjob.md)|Read the properties and relationships of a [printJob](../resources/printjob.md) object.|
|[Delete jobs](../api/printer-delete-jobs.md)|None|Delete a [printJob](../resources/printjob.md) object.|
|[List printJobs](../api/printjob-list.md)|[printJob](../resources/printjob.md) collection|Get a list of the [printJob](../resources/printjob.md) objects and their properties.|
|[Create printJob](../api/printjob-create.md)|[printJob](../resources/printjob.md)|Create a new [printJob](../resources/printjob.md) object.|
|[Get printJob](../api/printjob-get.md)|[printJob](../resources/printjob.md)|Read the properties and relationships of a [printJob](../resources/printjob.md) object.|
|[Update printJob](../api/printjob-update.md)|[printJob](../resources/printjob.md)|Update the properties of a [printJob](../resources/printjob.md) object.|
|[Delete printJob](../api/printjob-delete.md)|None|Deletes a [printJob](../resources/printjob.md) object.|
|[redirect](../api/printjob-redirect.md)|[printJob](../resources/printjob.md)|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|configuration|[printJobConfiguration](../resources/printjobconfiguration.md)|**TODO: Add Description**|
|createdBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|isFetchable|Boolean|**TODO: Add Description**|
|redirectedFrom|String|**TODO: Add Description**|
|redirectedTo|String|**TODO: Add Description**|
|status|[printJobStatus](../resources/printjobstatus.md)|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|documents|[printDocument](../resources/printdocument.md) collection|**TODO: Add Description**|
|tasks|[printTask](../resources/printtask.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.printJob",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.printJob",
  "id": "String (identifier)",
  "createdDateTime": "String (timestamp)",
  "status": {
    "@odata.type": "microsoft.graph.printJobStatus"
  },
  "createdBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "configuration": {
    "@odata.type": "microsoft.graph.printJobConfiguration"
  },
  "redirectedTo": "String",
  "redirectedFrom": "String",
  "isFetchable": "Boolean"
}
```

