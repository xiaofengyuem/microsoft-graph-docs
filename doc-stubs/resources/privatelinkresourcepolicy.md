---
title: "privateLinkResourcePolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# privateLinkResourcePolicy resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List privateLinkResourcePolicies](../api/policyroot-list-privatelinkresourcepolicies.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) collection|Get the privateLinkResourcePolicy resources from the privateLinkResourcePolicies navigation property.|
|[Create privateLinkResourcePolicies](../api/policyroot-post-privatelinkresourcepolicies.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Create a new privateLinkResourcePolicy object.|
|[Update privateLinkResourcePolicies](../api/policyroot-update-privatelinkresourcepolicies.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Update the properties of a privateLinkResourcePolicies object.|
|[Get privateLinkResourcePolicies](../api/policyroot-get-privatelinkresourcepolicy.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Read the properties and relationships of a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|
|[Delete privateLinkResourcePolicies](../api/policyroot-delete-privatelinkresourcepolicies.md)|None|Delete a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|
|[List privateLinkResourcePolicies](../api/privatelinkresourcepolicy-list.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) collection|Get a list of the [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) objects and their properties.|
|[Create privateLinkResourcePolicy](../api/privatelinkresourcepolicy-create.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Create a new [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|
|[Get privateLinkResourcePolicy](../api/privatelinkresourcepolicy-get.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Read the properties and relationships of a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|
|[Update privateLinkResourcePolicy](../api/privatelinkresourcepolicy-update.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Update the properties of a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|
|[Delete privateLinkResourcePolicy](../api/privatelinkresourcepolicy-delete.md)|None|Deletes a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|externalPrivateLinkId|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|tenantApprovals|[tenantApprovals](../resources/tenantapprovals.md) collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.privateLinkResourcePolicy",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.privateLinkResourcePolicy",
  "id": "String (identifier)",
  "externalPrivateLinkId": "String",
  "tenantApprovals": [
    {
      "@odata.type": "microsoft.graph.tenantApprovals"
    }
  ]
}
```

