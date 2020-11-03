---
title: "identityUserFlowAttribute resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityUserFlowAttribute resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userFlowAttributes](../api/identitycontainer-list-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|Get the identityUserFlowAttribute resources from the userFlowAttributes navigation property.|
|[Create userFlowAttributes](../api/identitycontainer-post-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Create a new identityUserFlowAttribute object.|
|[Update userFlowAttributes](../api/identitycontainer-update-userflowattributes.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Update the properties of a userFlowAttributes object.|
|[Get userFlowAttributes](../api/identitycontainer-get-identityuserflowattribute.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Read the properties and relationships of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Delete userFlowAttributes](../api/identitycontainer-delete-userflowattributes.md)|None|Delete an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[List identityUserFlowAttributes](../api/identityuserflowattribute-list.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md) collection|Get a list of the [identityUserFlowAttribute](../resources/identityuserflowattribute.md) objects and their properties.|
|[Create identityUserFlowAttribute](../api/identityuserflowattribute-create.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Create a new [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Get identityUserFlowAttribute](../api/identityuserflowattribute-get.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Read the properties and relationships of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Update identityUserFlowAttribute](../api/identityuserflowattribute-update.md)|[identityUserFlowAttribute](../resources/identityuserflowattribute.md)|Update the properties of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|
|[Delete identityUserFlowAttribute](../api/identityuserflowattribute-delete.md)|None|Deletes an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|dataType|identityUserFlowAttributeDataType|**TODO: Add Description**. Possible values are: `string`, `boolean`, `int64`, `stringCollection`, `dateTime`, `unknownFutureValue`.|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|userFlowAttributeType|identityUserFlowAttributeType|**TODO: Add Description**. Possible values are: `builtIn`, `custom`, `required`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityUserFlowAttribute",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityUserFlowAttribute",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```

