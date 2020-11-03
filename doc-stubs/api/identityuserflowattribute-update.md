---
title: "Update identityUserFlowAttribute"
description: "Update the properties of an identityUserFlowAttribute object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update identityUserFlowAttribute
Namespace: microsoft.graph

Update the properties of an [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.

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
PATCH /identity/userFlowAttributes/{identityUserFlowAttributeId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object.

The following table shows the properties that are required when you create the [identityUserFlowAttribute](../resources/identityuserflowattribute.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|userFlowAttributeType|identityUserFlowAttributeType|**TODO: Add Description**. Possible values are: `builtIn`, `custom`, `required`, `unknownFutureValue`.|
|dataType|identityUserFlowAttributeDataType|**TODO: Add Description**. Possible values are: `string`, `boolean`, `int64`, `stringCollection`, `dateTime`, `unknownFutureValue`.|



## Response

If successful, this method returns a `200 OK` response code and an updated [identityUserFlowAttribute](../resources/identityuserflowattribute.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_identityuserflowattribute"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/identity/userFlowAttributes/{identityUserFlowAttributeId}
Content-Type: application/json
Content-length: 186

{
  "@odata.type": "#microsoft.graph.identityUserFlowAttribute",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
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
  "@odata.type": "#microsoft.graph.identityUserFlowAttribute",
  "id": "e4e2d62e-d62e-e4e2-2ed6-e2e42ed6e2e4",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```

