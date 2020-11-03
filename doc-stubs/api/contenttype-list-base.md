---
title: "List base"
description: "Get the contentType resources from the base navigation property."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List base
Namespace: microsoft.graph

Get the contentType resources from the base navigation property.

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
GET /drive/list/contentTypes
GET /sites/{sitesId}/contentTypes
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

If successful, this method returns a `200 OK` response code and a collection of [contentType](../resources/contenttype.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_contenttype"
}
-->
``` http
GET https://graph.microsoft.com/beta/drive/list/contentTypes
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.contentType)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.contentType",
      "id": "7d1a1a74-1a74-7d1a-741a-1a7d741a1a7d",
      "associatedHubUrls": [
        "String"
      ],
      "description": "String",
      "documentSet": {
        "@odata.type": "microsoft.graph.documentSet"
      },
      "documentTemplate": {
        "@odata.type": "microsoft.graph.documentSetContent"
      },
      "group": "String",
      "hidden": "Boolean",
      "inheritedFrom": {
        "@odata.type": "microsoft.graph.itemReference"
      },
      "isBuiltIn": "Boolean",
      "name": "String",
      "order": {
        "@odata.type": "microsoft.graph.contentTypeOrder"
      },
      "parentId": "String",
      "propagateChanges": "Boolean",
      "readOnly": "Boolean",
      "sealed": "Boolean"
    }
  ]
}
```

