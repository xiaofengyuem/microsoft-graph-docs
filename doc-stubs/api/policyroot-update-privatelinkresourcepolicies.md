---
title: "Update privateLinkResourcePolicies"
description: "Update the properties of a privateLinkResourcePolicies object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update privateLinkResourcePolicies
Namespace: microsoft.graph

Update the properties of a privateLinkResourcePolicies object.

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
PATCH /policyRoot/privateLinkResourcePolicies
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
|id|String|**TODO: Add Description**|
|externalPrivateLinkId|String|**TODO: Add Description**|
|tenantApprovals|[tenantApprovals](../resources/tenantapprovals.md) collection|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_privatelinkresourcepolicies"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/policyRoot/privateLinkResourcePolicies
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
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.privateLinkResourcePolicy",
  "id": "ee656471-6471-ee65-7164-65ee716465ee",
  "externalPrivateLinkId": "String",
  "tenantApprovals": [
    {
      "@odata.type": "microsoft.graph.tenantApprovals"
    }
  ]
}
```

