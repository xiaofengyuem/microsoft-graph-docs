---
title: "Update agreementFileProperties"
description: "Update the properties of an agreementFileProperties object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update agreementFileProperties
Namespace: microsoft.graph

Update the properties of an [agreementFileProperties](../resources/agreementfileproperties.md) object.

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
PATCH /agreementFileProperties
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [agreementFileProperties](../resources/agreementfileproperties.md) object.

The following table shows the properties that are required when you create the [agreementFileProperties](../resources/agreementfileproperties.md).

|Property|Type|Description|
|:---|:---|:---|
|fileName|String|**TODO: Add Description**|
|language|String|**TODO: Add Description**|
|isDefault|Boolean|**TODO: Add Description**|
|isMajorVersion|Boolean|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|fileData|[agreementFileData](../resources/agreementfiledata.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [agreementFileProperties](../resources/agreementfileproperties.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_agreementfileproperties"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/agreementFileProperties
Content-Type: application/json
Content-length: 253

{
  "@odata.type": "#microsoft.graph.agreementFileProperties",
  "fileName": "String",
  "language": "String",
  "isDefault": "Boolean",
  "isMajorVersion": "Boolean",
  "fileData": {
    "@odata.type": "microsoft.graph.agreementFileData"
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

