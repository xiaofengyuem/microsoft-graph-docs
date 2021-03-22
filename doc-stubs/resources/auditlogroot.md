---
title: "auditLogRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# auditLogRoot resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get auditLogRoot](../api/auditlogroot-get.md)|[auditLogRoot](../resources/auditlogroot.md)|Read the properties and relationships of an [auditLogRoot](../resources/auditlogroot.md) object.|
|[Update auditLogRoot](../api/auditlogroot-update.md)|[auditLogRoot](../resources/auditlogroot.md)|Update the properties of an [auditLogRoot](../resources/auditlogroot.md) object.|
|[List provisioning](../api/auditlogroot-list-provisioning.md)|[provisioningObjectSummary](../resources/provisioningobjectsummary.md) collection|Get the provisioningObjectSummary resources from the provisioning navigation property.|
|[Create provisioningObjectSummary](../api/auditlogroot-post-provisioning.md)|[provisioningObjectSummary](../resources/provisioningobjectsummary.md)|Create a new provisioningObjectSummary object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|directoryAudits|[directoryAudit](../resources/directoryaudit.md) collection|**TODO: Add Description**|
|provisioning|[provisioningObjectSummary](../resources/provisioningobjectsummary.md) collection|**TODO: Add Description**|
|restrictedSignIns|[restrictedSignIn](../resources/restrictedsignin.md) collection|**TODO: Add Description**|
|signIns|[signIn](../resources/signin.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.auditLogRoot",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.auditLogRoot"
}
```

