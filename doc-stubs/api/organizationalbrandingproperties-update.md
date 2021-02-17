---
title: "Update organizationalBrandingProperties"
description: "Update the properties of an organizationalBrandingProperties object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update organizationalBrandingProperties
Namespace: microsoft.graph



Update the properties of an [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.

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
PATCH /organizationalBrandingProperties
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object.

The following table shows the properties that are required when you update the [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|backgroundColor|String|**TODO: Add Description**|
|backgroundImage|Stream|**TODO: Add Description**|
|bannerLogo|Stream|**TODO: Add Description**|
|signInPageText|String|**TODO: Add Description**|
|squareLogo|Stream|**TODO: Add Description**|
|usernameHintText|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_organizationalbrandingproperties"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/organizationalBrandingProperties
Content-Type: application/json
Content-length: 256

{
  "@odata.type": "#microsoft.graph.organizationalBrandingProperties",
  "backgroundColor": "String",
  "backgroundImage": "Stream",
  "bannerLogo": "Stream",
  "signInPageText": "String",
  "squareLogo": "Stream",
  "usernameHintText": "String"
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
  "@odata.type": "#microsoft.graph.organizationalBrandingProperties",
  "id": "2d639bc0-9bc0-2d63-c09b-632dc09b632d",
  "backgroundColor": "String",
  "backgroundImage": "Stream",
  "bannerLogo": "Stream",
  "signInPageText": "String",
  "squareLogo": "Stream",
  "usernameHintText": "String"
}
```

