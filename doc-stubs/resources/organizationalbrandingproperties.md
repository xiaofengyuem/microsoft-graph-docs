---
title: "organizationalBrandingProperties resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# organizationalBrandingProperties resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List organizationalBrandingProperties](../api/organizationalbrandingproperties-list.md)|[organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) collection|Get a list of the [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) objects and their properties.|
|[Create organizationalBrandingProperties](../api/organizationalbrandingproperties-create.md)|[organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|Create a new [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.|
|[Get organizationalBrandingProperties](../api/organizationalbrandingproperties-get.md)|[organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|Read the properties and relationships of an [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.|
|[Update organizationalBrandingProperties](../api/organizationalbrandingproperties-update.md)|[organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|Update the properties of an [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.|
|[Delete organizationalBrandingProperties](../api/organizationalbrandingproperties-delete.md)|None|Deletes an [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|backgroundColor|String|**TODO: Add Description**|
|backgroundImage|Stream|**TODO: Add Description**|
|bannerLogo|Stream|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|signInPageText|String|**TODO: Add Description**|
|squareLogo|Stream|**TODO: Add Description**|
|usernameHintText|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.organizationalBrandingProperties",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.organizationalBrandingProperties",
  "id": "String (identifier)",
  "backgroundColor": "String",
  "backgroundImage": "Stream",
  "bannerLogo": "Stream",
  "signInPageText": "String",
  "squareLogo": "Stream",
  "usernameHintText": "String"
}
```

