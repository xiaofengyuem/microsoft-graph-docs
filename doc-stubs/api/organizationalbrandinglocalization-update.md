---
title: "Update organizationalBrandingLocalization"
description: "Update the properties of an organizationalBrandingLocalization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update organizationalBrandingLocalization
Namespace: microsoft.graph



Update the properties of an [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md) object.

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
PATCH /localizations/{localizationsId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md) object.

The following table shows the properties that are required when you update the [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|backgroundColor|String|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|backgroundImage|Stream|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|bannerLogo|Stream|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|signInPageText|String|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|squareLogo|Stream|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|
|usernameHintText|String|**TODO: Add Description** Inherited from [organizationalBrandingProperties](../resources/organizationalbrandingproperties.md)|



## Response

If successful, this method returns a `200 OK` response code and an updated [organizationalBrandingLocalization](../resources/organizationalbrandinglocalization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_organizationalbrandinglocalization"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/localizations/{localizationsId}
Content-Type: application/json
Content-length: 258

{
  "@odata.type": "#microsoft.graph.organizationalBrandingLocalization",
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
  "@odata.type": "#microsoft.graph.organizationalBrandingLocalization",
  "id": "851f1d49-1d49-851f-491d-1f85491d1f85",
  "backgroundColor": "String",
  "backgroundImage": "Stream",
  "bannerLogo": "Stream",
  "signInPageText": "String",
  "squareLogo": "Stream",
  "usernameHintText": "String"
}
```

