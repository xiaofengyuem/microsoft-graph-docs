---
title: "identityCustomUserFlowAttribute resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityCustomUserFlowAttribute resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [identityUserFlowAttribute](../resources/identityuserflowattribute.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityCustomUserFlowAttributes](../api/identitycustomuserflowattribute-list.md)|[identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) collection|Get a list of the [identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) objects and their properties.|
|[Create identityCustomUserFlowAttribute](../api/identitycustomuserflowattribute-create.md)|[identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md)|Create a new [identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) object.|
|[Get identityCustomUserFlowAttribute](../api/identitycustomuserflowattribute-get.md)|[identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md)|Read the properties and relationships of an [identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) object.|
|[Update identityCustomUserFlowAttribute](../api/identitycustomuserflowattribute-update.md)|[identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md)|Update the properties of an [identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) object.|
|[Delete identityCustomUserFlowAttribute](../api/identitycustomuserflowattribute-delete.md)|None|Deletes an [identityCustomUserFlowAttribute](../resources/identitycustomuserflowattribute.md) object.|

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
  "@odata.type": "microsoft.graph.identityCustomUserFlowAttribute",
  "baseType": "microsoft.graph.identityUserFlowAttribute",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityCustomUserFlowAttribute",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```

