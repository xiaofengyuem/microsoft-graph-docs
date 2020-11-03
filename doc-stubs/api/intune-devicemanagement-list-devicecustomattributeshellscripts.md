---
title: "List deviceCustomAttributeShellScripts"
description: "Get the deviceCustomAttributeShellScript resources from the deviceCustomAttributeShellScripts navigation property."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List deviceCustomAttributeShellScripts
Namespace: microsoft.graph

Get the deviceCustomAttributeShellScript resources from the deviceCustomAttributeShellScripts navigation property.

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
GET /deviceManagement/deviceCustomAttributeShellScripts
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [deviceCustomAttributeShellScript](../resources/devicecustomattributeshellscript.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_devicecustomattributeshellscript"
}
-->
``` http
GET https://graph.microsoft.com/beta/deviceManagement/deviceCustomAttributeShellScripts
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.deviceCustomAttributeShellScript)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.deviceCustomAttributeShellScript",
      "id": "651a1b4a-1b4a-651a-4a1b-1a654a1b1a65",
      "customAttributeName": "String",
      "customAttributeType": "String",
      "displayName": "String",
      "description": "String",
      "scriptContent": "Binary",
      "createdDateTime": "String (timestamp)",
      "lastModifiedDateTime": "String (timestamp)",
      "runAsAccount": "String",
      "fileName": "String",
      "roleScopeTagIds": [
        "String"
      ]
    }
  ]
}
```

