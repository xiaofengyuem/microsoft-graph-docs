---
title: "agreementFileProperties resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreementFileProperties resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreementFileProperties](../api/agreementfileproperties-list.md)|[agreementFileProperties](../resources/agreementfileproperties.md) collection|Get a list of the [agreementFileProperties](../resources/agreementfileproperties.md) objects and their properties.|
|[Create agreementFileProperties](../api/agreementfileproperties-create.md)|[agreementFileProperties](../resources/agreementfileproperties.md)|Create a new [agreementFileProperties](../resources/agreementfileproperties.md) object.|
|[Get agreementFileProperties](../api/agreementfileproperties-get.md)|[agreementFileProperties](../resources/agreementfileproperties.md)|Read the properties and relationships of an [agreementFileProperties](../resources/agreementfileproperties.md) object.|
|[Update agreementFileProperties](../api/agreementfileproperties-update.md)|[agreementFileProperties](../resources/agreementfileproperties.md)|Update the properties of an [agreementFileProperties](../resources/agreementfileproperties.md) object.|
|[Delete agreementFileProperties](../api/agreementfileproperties-delete.md)|None|Deletes an [agreementFileProperties](../resources/agreementfileproperties.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|fileData|[agreementFileData](../resources/agreementfiledata.md)|**TODO: Add Description**|
|fileName|String|**TODO: Add Description**|
|isDefault|Boolean|**TODO: Add Description**|
|isMajorVersion|Boolean|**TODO: Add Description**|
|language|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreementFileProperties",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreementFileProperties",
  "fileName": "String",
  "language": "String",
  "isDefault": "Boolean",
  "isMajorVersion": "Boolean",
  "createdDateTime": "String (timestamp)",
  "fileData": {
    "@odata.type": "microsoft.graph.agreementFileData"
  }
}
```

