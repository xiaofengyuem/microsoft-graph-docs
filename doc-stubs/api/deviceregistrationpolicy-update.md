---
title: "Update deviceRegistrationPolicy"
description: "Update the properties of a deviceRegistrationPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update deviceRegistrationPolicy
Namespace: microsoft.graph

Update the properties of a [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.

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
PATCH /deviceRegistrationPolicy
PATCH /policyRoot/deviceRegistrationPolicy
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object.

The following table shows the properties that are required when you create the [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|userDeviceQuota|Int32|**TODO: Add Description**|
|multiFactorAuthConfiguration|multiFactorAuthConfiguration|**TODO: Add Description**. Possible values are: `notRequired`, `required`, `unknownFutureValue`.|
|azureADRegistration|[azureADRegistrationPolicy](../resources/azureadregistrationpolicy.md)|**TODO: Add Description**|
|azureADJoin|[azureAdJoinPolicy](../resources/azureadjoinpolicy.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [deviceRegistrationPolicy](../resources/deviceregistrationpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_deviceregistrationpolicy"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceRegistrationPolicy
Content-Type: application/json
Content-length: 380

{
  "@odata.type": "#microsoft.graph.deviceRegistrationPolicy",
  "displayName": "String",
  "description": "String",
  "userDeviceQuota": "Integer",
  "multiFactorAuthConfiguration": "String",
  "azureADRegistration": {
    "@odata.type": "microsoft.graph.azureADRegistrationPolicy"
  },
  "azureADJoin": {
    "@odata.type": "microsoft.graph.azureAdJoinPolicy"
  }
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
  "@odata.type": "#microsoft.graph.deviceRegistrationPolicy",
  "id": "9ecffd12-fd12-9ecf-12fd-cf9e12fdcf9e",
  "displayName": "String",
  "description": "String",
  "userDeviceQuota": "Integer",
  "multiFactorAuthConfiguration": "String",
  "azureADRegistration": {
    "@odata.type": "microsoft.graph.azureADRegistrationPolicy"
  },
  "azureADJoin": {
    "@odata.type": "microsoft.graph.azureAdJoinPolicy"
  }
}
```

