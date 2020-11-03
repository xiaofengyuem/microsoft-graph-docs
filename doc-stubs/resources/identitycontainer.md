---
title: "identityContainer resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityContainer resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityContainers](../api/identitycontainer-list.md)|[identityContainer](../resources/identitycontainer.md) collection|Get a list of the [identityContainer](../resources/identitycontainer.md) objects and their properties.|
|[Create identityContainer](../api/identitycontainer-create.md)|[identityContainer](../resources/identitycontainer.md)|Create a new [identityContainer](../resources/identitycontainer.md) object.|
|[Get identityContainer](../api/identitycontainer-get.md)|[identityContainer](../resources/identitycontainer.md)|Read the properties and relationships of an [identityContainer](../resources/identitycontainer.md) object.|
|[Update identityContainer](../api/identitycontainer-update.md)|[identityContainer](../resources/identitycontainer.md)|Update the properties of an [identityContainer](../resources/identitycontainer.md) object.|
|[Delete identityContainer](../api/identitycontainer-delete.md)|None|Deletes an [identityContainer](../resources/identitycontainer.md) object.|
|[List userFlowAttributes](../api/identitycontainer-list-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|Get the identityUserFlowAttribute resources from the userFlowAttributes navigation property.|
|[Create userFlowAttributes](../api/identitycontainer-post-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Create a new identityUserFlowAttribute object.|
|[Get userFlowAttributes](../api/identitycontainer-get-identityuserflowattribute.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Read the properties and relationships of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Update userFlowAttributes](../api/identitycontainer-update-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Update the properties of a userFlowAttributes object.|
|[Delete userFlowAttributes](../api/identitycontainer-delete-userflowattributes.md)|None|Delete an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|b2cUserFlows|[b2cIdentityUserFlow](../resources/b2cidentityuserflow.md) collection|**TODO: Add Description**|
|b2xUserFlows|[b2xIdentityUserFlow](../resources/b2xidentityuserflow.md) collection|**TODO: Add Description**|
|conditionalAccess|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|**TODO: Add Description**|
|continuousAccessEvaluationPolicy|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|**TODO: Add Description**|
|userFlowAttributes|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|**TODO: Add Description**|
|userFlows|[identityUserFlow](../resources/identityuserflow.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityContainer",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityContainer"
}
```

