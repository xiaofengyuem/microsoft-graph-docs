---
title: "Update auditLogRoot"
description: "Update the properties of an auditLogRoot object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update auditLogRoot
Namespace: microsoft.graph



Update the properties of an [auditLogRoot](../resources/auditlogroot.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
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
PATCH /auditLogs
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [auditLogRoot](../resources/auditlogroot.md) object.

The following table shows the properties that are required when you update the [auditLogRoot](../resources/auditlogroot.md).

|Property|Type|Description|
|:---|:---|:---|



## Response

If successful, this method returns a `200 OK` response code and an updated [auditLogRoot](../resources/auditlogroot.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_auditlogroot"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/auditLogs
Content-Type: application/json
Content-length: 54

{
  "@odata.type": "#microsoft.graph.auditLogRoot"
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
  "@odata.type": "#microsoft.graph.auditLogRoot"
}
```

