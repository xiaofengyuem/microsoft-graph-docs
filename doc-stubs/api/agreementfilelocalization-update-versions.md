---
title: "Update versions"
description: "Update the properties of a versions object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update versions
Namespace: microsoft.graph

Update the properties of a versions object.

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
PATCH /agreements/{agreementsId}/file/localizations/{agreementFileLocalizationId}/versions
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [agreementFileVersion](../resources/agreementfileversion.md) object.

The following table shows the properties that are required when you create the [agreementFileVersion](../resources/agreementfileversion.md).

|Property|Type|Description|
|:---|:---|:---|
|fileName|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|language|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|isDefault|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|isMajorVersion|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|fileData|[agreementFileData](../resources/agreementfiledata.md)|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|



## Response

If successful, this method returns a `200 OK` response code and an updated [agreementFileVersion](../resources/agreementfileversion.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_versions"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/agreements/{agreementsId}/file/localizations/{agreementFileLocalizationId}/versions
Content-Type: application/json
Content-length: 250

{
  "@odata.type": "#microsoft.graph.agreementFileVersion",
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
  "@odata.type": "#microsoft.graph.agreementFileVersion",
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

