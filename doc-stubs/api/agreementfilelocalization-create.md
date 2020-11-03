---
title: "Create agreementFileLocalization"
description: "Create a new agreementFileLocalization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create agreementFileLocalization
Namespace: microsoft.graph

Create a new [agreementFileLocalization](../resources/agreementfilelocalization.md) object.

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
POST /agreements/{agreementsId}/files
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [agreementFileLocalization](../resources/agreementfilelocalization.md) object.

The following table shows the properties that are required when you create the [agreementFileLocalization](../resources/agreementfilelocalization.md).

|Property|Type|Description|
|:---|:---|:---|
|fileName|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|language|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|isDefault|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|isMajorVersion|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|
|fileData|[agreementFileData](../resources/agreementfiledata.md)|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md)|



## Response

If successful, this method returns a `201 Created` response code and an [agreementFileLocalization](../resources/agreementfilelocalization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_agreementfilelocalization_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/agreements/{agreementsId}/files
Content-Type: application/json
Content-length: 255

{
  "@odata.type": "#microsoft.graph.agreementFileLocalization",
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
  "truncated": true,
  "@odata.type": "microsoft.graph.agreementFileLocalization"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.agreementFileLocalization",
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

