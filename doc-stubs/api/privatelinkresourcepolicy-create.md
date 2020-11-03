---
title: "Create privateLinkResourcePolicy"
description: "Create a new privateLinkResourcePolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create privateLinkResourcePolicy
Namespace: microsoft.graph

Create a new [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.

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
POST /policies/privateLinkResourcePolicies
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object.

The following table shows the properties that are required when you create the [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|externalPrivateLinkId|String|**TODO: Add Description**|
|tenantApprovals|[tenantApprovals](../resources/tenantapprovals.md) collection|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_privatelinkresourcepolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/policies/privateLinkResourcePolicies
Content-Type: application/json
Content-length: 205

{
  "@odata.type": "#microsoft.graph.privateLinkResourcePolicy",
  "externalPrivateLinkId": "String",
  "tenantApprovals": [
    {
      "@odata.type": "microsoft.graph.tenantApprovals"
    }
  ]
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.privateLinkResourcePolicy"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.privateLinkResourcePolicy",
  "id": "c284f1a5-f1a5-c284-a5f1-84c2a5f184c2",
  "externalPrivateLinkId": "String",
  "tenantApprovals": [
    {
      "@odata.type": "microsoft.graph.tenantApprovals"
    }
  ]
}
```

