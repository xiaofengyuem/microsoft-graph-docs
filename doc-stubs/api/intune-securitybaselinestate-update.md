---
title: "Update securityBaselineState"
description: "Update the properties of a securityBaselineState object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update securityBaselineState
Namespace: microsoft.graph

Update the properties of a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.

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
PATCH /me/managedDevices/{managedDeviceId}/securityBaselineStates/{securityBaselineStateId}
PATCH /users/{usersId}/managedDevices/{managedDeviceId}/securityBaselineStates/{securityBaselineStateId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [securityBaselineState](../resources/intune-securitybaselinestate.md) object.

The following table shows the properties that are required when you create the [securityBaselineState](../resources/intune-securitybaselinestate.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|securityBaselineTemplateId|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|state|securityBaselineComplianceState|**TODO: Add Description**. Possible values are: `unknown`, `secure`, `notApplicable`, `notSecure`, `error`, `conflict`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [securityBaselineState](../resources/intune-securitybaselinestate.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_securitybaselinestate"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/me/managedDevices/{managedDeviceId}/securityBaselineStates/{securityBaselineStateId}
Content-Type: application/json
Content-length: 190

{
  "@odata.type": "#microsoft.graph.securityBaselineState",
  "securityBaselineTemplateId": "String",
  "userPrincipalName": "String",
  "displayName": "String",
  "state": "String"
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
  "@odata.type": "#microsoft.graph.securityBaselineState",
  "id": "0eaaeac2-eac2-0eaa-c2ea-aa0ec2eaaa0e",
  "securityBaselineTemplateId": "String",
  "userPrincipalName": "String",
  "displayName": "String",
  "state": "String"
}
```

