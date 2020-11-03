---
title: "windowsHelloForBusinessAuthenticationMethod resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windowsHelloForBusinessAuthenticationMethod resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [authenticationMethod](../resources/authenticationmethod.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List windowsHelloForBusinessMethods](../api/authentication-list-windowshelloforbusinessmethods.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) collection|Get the windowsHelloForBusinessAuthenticationMethod resources from the windowsHelloForBusinessMethods navigation property.|
|[Create windowsHelloForBusinessMethods](../api/authentication-post-windowshelloforbusinessmethods.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Create a new windowsHelloForBusinessAuthenticationMethod object.|
|[Update windowsHelloForBusinessMethods](../api/authentication-update-windowshelloforbusinessmethods.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Update the properties of a windowsHelloForBusinessMethods object.|
|[Get windowsHelloForBusinessMethods](../api/authentication-get-windowshelloforbusinessauthenticationmethod.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Read the properties and relationships of a [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[Delete windowsHelloForBusinessMethods](../api/authentication-delete-windowshelloforbusinessmethods.md)|None|Delete a [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[List windowsHelloForBusinessAuthenticationMethods](../api/windowshelloforbusinessauthenticationmethod-list.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) collection|Get a list of the [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) objects and their properties.|
|[Create windowsHelloForBusinessAuthenticationMethod](../api/windowshelloforbusinessauthenticationmethod-create.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Create a new [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[Get windowsHelloForBusinessAuthenticationMethod](../api/windowshelloforbusinessauthenticationmethod-get.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Read the properties and relationships of a [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[Update windowsHelloForBusinessAuthenticationMethod](../api/windowshelloforbusinessauthenticationmethod-update.md)|[windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md)|Update the properties of a [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[Delete windowsHelloForBusinessAuthenticationMethod](../api/windowshelloforbusinessauthenticationmethod-delete.md)|None|Deletes a [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.|
|[enableSmsSignIn](../api/windowshelloforbusinessauthenticationmethod-enablesmssignin.md)|None|**TODO: Add Description**|
|[disableSmsSignIn](../api/windowshelloforbusinessauthenticationmethod-disablesmssignin.md)|None|**TODO: Add Description**|
|[resetPassword](../api/windowshelloforbusinessauthenticationmethod-resetpassword.md)|[passwordResetResponse](../resources/passwordresetresponse.md)|**TODO: Add Description**|
|[List device](../api/windowshelloforbusinessauthenticationmethod-list-device.md)|[device](../resources/device.md) collection|Get the device resources from the device navigation property.|
|[Create device](../api/windowshelloforbusinessauthenticationmethod-post-device.md)|[device](../resources/device.md)|Create a new device object.|
|[Get device](../api/windowshelloforbusinessauthenticationmethod-get-device.md)|[device](../resources/device.md)|Read the properties and relationships of a [device](../resources/device.md) object.|
|[Update device](../api/windowshelloforbusinessauthenticationmethod-update-device.md)|[device](../resources/device.md)|Update the properties of a device object.|
|[Delete device](../api/windowshelloforbusinessauthenticationmethod-delete-device.md)|None|Delete a [device](../resources/device.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|keyStrength|authenticationMethodKeyStrength|**TODO: Add Description**. Possible values are: `normal`, `weak`, `unknown`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|device|[device](../resources/device.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsHelloForBusinessAuthenticationMethod",
  "baseType": "microsoft.graph.authenticationMethod",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsHelloForBusinessAuthenticationMethod",
  "id": "String (identifier)",
  "displayName": "String",
  "creationDateTime": "String (timestamp)",
  "keyStrength": "String"
}
```

