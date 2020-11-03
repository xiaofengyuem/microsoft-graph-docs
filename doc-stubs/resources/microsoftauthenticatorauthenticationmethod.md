---
title: "microsoftAuthenticatorAuthenticationMethod resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# microsoftAuthenticatorAuthenticationMethod resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [authenticationMethod](../resources/authenticationmethod.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List microsoftAuthenticatorMethods](../api/authentication-list-microsoftauthenticatormethods.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) collection|Get the microsoftAuthenticatorAuthenticationMethod resources from the microsoftAuthenticatorMethods navigation property.|
|[Create microsoftAuthenticatorMethods](../api/authentication-post-microsoftauthenticatormethods.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Create a new microsoftAuthenticatorAuthenticationMethod object.|
|[Update microsoftAuthenticatorMethods](../api/authentication-update-microsoftauthenticatormethods.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Update the properties of a microsoftAuthenticatorMethods object.|
|[Get microsoftAuthenticatorMethods](../api/authentication-get-microsoftauthenticatorauthenticationmethod.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Read the properties and relationships of a [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[Delete microsoftAuthenticatorMethods](../api/authentication-delete-microsoftauthenticatormethods.md)|None|Delete a [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[List microsoftAuthenticatorAuthenticationMethods](../api/microsoftauthenticatorauthenticationmethod-list.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) collection|Get a list of the [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) objects and their properties.|
|[Create microsoftAuthenticatorAuthenticationMethod](../api/microsoftauthenticatorauthenticationmethod-create.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Create a new [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[Get microsoftAuthenticatorAuthenticationMethod](../api/microsoftauthenticatorauthenticationmethod-get.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Read the properties and relationships of a [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[Update microsoftAuthenticatorAuthenticationMethod](../api/microsoftauthenticatorauthenticationmethod-update.md)|[microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md)|Update the properties of a [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[Delete microsoftAuthenticatorAuthenticationMethod](../api/microsoftauthenticatorauthenticationmethod-delete.md)|None|Deletes a [microsoftAuthenticatorAuthenticationMethod](../resources/microsoftauthenticatorauthenticationmethod.md) object.|
|[List device](../api/microsoftauthenticatorauthenticationmethod-list-device.md)|[device](../resources/device.md) collection|Get the device resources from the device navigation property.|
|[Create device](../api/microsoftauthenticatorauthenticationmethod-post-device.md)|[device](../resources/device.md)|Create a new device object.|
|[Get device](../api/microsoftauthenticatorauthenticationmethod-get-device.md)|[device](../resources/device.md)|Read the properties and relationships of a [device](../resources/device.md) object.|
|[Update device](../api/microsoftauthenticatorauthenticationmethod-update-device.md)|[device](../resources/device.md)|Update the properties of a device object.|
|[Delete device](../api/microsoftauthenticatorauthenticationmethod-delete-device.md)|None|Delete a [device](../resources/device.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|deviceTag|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|phoneAppVersion|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|device|[device](../resources/device.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.microsoftAuthenticatorAuthenticationMethod",
  "baseType": "microsoft.graph.authenticationMethod",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.microsoftAuthenticatorAuthenticationMethod",
  "id": "String (identifier)",
  "displayName": "String",
  "deviceTag": "String",
  "phoneAppVersion": "String",
  "creationDateTime": "String (timestamp)"
}
```

