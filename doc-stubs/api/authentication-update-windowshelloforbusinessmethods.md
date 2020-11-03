---
title: "Update windowsHelloForBusinessMethods"
description: "Update the properties of a windowsHelloForBusinessMethods object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update windowsHelloForBusinessMethods
Namespace: microsoft.graph

Update the properties of a windowsHelloForBusinessMethods object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /users/{usersId}/authentication/windowsHelloForBusinessMethods
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object.

The following table shows the properties that are required when you create the [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|keyStrength|authenticationMethodKeyStrength|**TODO: Add Description**. Possible values are: `normal`, `weak`, `unknown`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [windowsHelloForBusinessAuthenticationMethod](../resources/windowshelloforbusinessauthenticationmethod.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_windowshelloforbusinessmethods"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/users/{usersId}/authentication/windowsHelloForBusinessMethods
Content-Type: application/json
Content-length: 186

{
  "@odata.type": "#microsoft.graph.windowsHelloForBusinessAuthenticationMethod",
  "displayName": "String",
  "creationDateTime": "String (timestamp)",
  "keyStrength": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.windowsHelloForBusinessAuthenticationMethod",
  "id": "c9db95d6-95d6-c9db-d695-dbc9d695dbc9",
  "displayName": "String",
  "creationDateTime": "String (timestamp)",
  "keyStrength": "String"
}
```

