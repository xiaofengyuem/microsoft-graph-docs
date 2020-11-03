---
title: "Create macOSSoftwareUpdateAccountSummaries"
description: "Create a new macOSSoftwareUpdateAccountSummary object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create macOSSoftwareUpdateAccountSummaries
Namespace: microsoft.graph

Create a new macOSSoftwareUpdateAccountSummary object.

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
POST /deviceManagement/macOSSoftwareUpdateAccountSummaries
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object.

The following table shows the properties that are required when you create the [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|deviceId|String|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|deviceName|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|osVersion|String|**TODO: Add Description**|
|successfulUpdateCount|Int32|**TODO: Add Description**|
|failedUpdateCount|Int32|**TODO: Add Description**|
|totalUpdateCount|Int32|**TODO: Add Description**|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [macOSSoftwareUpdateAccountSummary](../resources/intune-macossoftwareupdateaccountsummary.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_macossoftwareupdateaccountsummary_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/deviceManagement/macOSSoftwareUpdateAccountSummaries
Content-Type: application/json
Content-length: 394

{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateAccountSummary",
  "displayName": "String",
  "deviceId": "String",
  "userId": "String",
  "deviceName": "String",
  "userPrincipalName": "String",
  "osVersion": "String",
  "successfulUpdateCount": "Integer",
  "failedUpdateCount": "Integer",
  "totalUpdateCount": "Integer",
  "lastUpdatedDateTime": "String (timestamp)"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateAccountSummary"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateAccountSummary",
  "id": "cb593109-3109-cb59-0931-59cb093159cb",
  "displayName": "String",
  "deviceId": "String",
  "userId": "String",
  "deviceName": "String",
  "userPrincipalName": "String",
  "osVersion": "String",
  "successfulUpdateCount": "Integer",
  "failedUpdateCount": "Integer",
  "totalUpdateCount": "Integer",
  "lastUpdatedDateTime": "String (timestamp)"
}
```

