---
title: "identityBuiltInUserFlowAttribute resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityBuiltInUserFlowAttribute resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [identityUserFlowAttribute](../resources/identityuserflowattribute.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityBuiltInUserFlowAttributes](../api/identitybuiltinuserflowattribute-list.md)|[identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) collection|Get a list of the [identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) objects and their properties.|
|[Create identityBuiltInUserFlowAttribute](../api/identitybuiltinuserflowattribute-create.md)|[identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md)|Create a new [identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) object.|
|[Get identityBuiltInUserFlowAttribute](../api/identitybuiltinuserflowattribute-get.md)|[identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md)|Read the properties and relationships of an [identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) object.|
|[Update identityBuiltInUserFlowAttribute](../api/identitybuiltinuserflowattribute-update.md)|[identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md)|Update the properties of an [identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) object.|
|[Delete identityBuiltInUserFlowAttribute](../api/identitybuiltinuserflowattribute-delete.md)|None|Deletes an [identityBuiltInUserFlowAttribute](../resources/identitybuiltinuserflowattribute.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|dataType|identityUserFlowAttributeDataType|**TODO: Add Description** Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Possible values are: `string`, `boolean`, `int64`, `stringCollection`, `dateTime`, `unknownFutureValue`.|
|description|String|**TODO: Add Description** Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md)|
|displayName|String|**TODO: Add Description** Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|userFlowAttributeType|identityUserFlowAttributeType|**TODO: Add Description** Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Possible values are: `builtIn`, `custom`, `required`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityBuiltInUserFlowAttribute",
  "baseType": "microsoft.graph.identityUserFlowAttribute",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityBuiltInUserFlowAttribute",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```

