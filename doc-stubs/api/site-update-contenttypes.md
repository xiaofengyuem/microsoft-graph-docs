---
title: "Update contentTypes"
description: "Update the properties of a contentTypes object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update contentTypes
Namespace: microsoft.graph

Update the properties of a contentTypes object.

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
PATCH /sites/{sitesId}/contentTypes
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [contentType](../resources/contenttype.md) object.

The following table shows the properties that are required when you create the [contentType](../resources/contenttype.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|description|String|**TODO: Add Description**|
|group|String|**TODO: Add Description**|
|hidden|Boolean|**TODO: Add Description**|
|inheritedFrom|[itemReference](../resources/itemreference.md)|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|order|[contentTypeOrder](../resources/contenttypeorder.md)|**TODO: Add Description**|
|parentId|String|**TODO: Add Description**|
|readOnly|Boolean|**TODO: Add Description**|
|sealed|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [contentType](../resources/contenttype.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_contenttypes"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/sites/{sitesId}/contentTypes
Content-Type: application/json
Content-length: 378

{
  "@odata.type": "#microsoft.graph.contentType",
  "description": "String",
  "group": "String",
  "hidden": "Boolean",
  "inheritedFrom": {
    "@odata.type": "microsoft.graph.itemReference"
  },
  "name": "String",
  "order": {
    "@odata.type": "microsoft.graph.contentTypeOrder"
  },
  "parentId": "String",
  "readOnly": "Boolean",
  "sealed": "Boolean"
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
  "@odata.type": "#microsoft.graph.contentType",
  "id": "7d1a1a74-1a74-7d1a-741a-1a7d741a1a7d",
  "description": "String",
  "group": "String",
  "hidden": "Boolean",
  "inheritedFrom": {
    "@odata.type": "microsoft.graph.itemReference"
  },
  "name": "String",
  "order": {
    "@odata.type": "microsoft.graph.contentTypeOrder"
  },
  "parentId": "String",
  "readOnly": "Boolean",
  "sealed": "Boolean"
}
```

