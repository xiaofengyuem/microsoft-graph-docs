---
title: "Get categorySummaries"
description: "Read the properties and relationships of a macOSSoftwareUpdateCategorySummary object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get categorySummaries
Namespace: microsoft.graph

Read the properties and relationships of a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.

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
GET /deviceManagement/macOSSoftwareUpdateAccountSummaries/{macOSSoftwareUpdateAccountSummaryId}/categorySummaries
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

If successful, this method returns a `200 OK` response code and a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_macossoftwareupdatecategorysummary"
}
-->
``` http
GET https://graph.microsoft.com/beta/deviceManagement/macOSSoftwareUpdateAccountSummaries/{macOSSoftwareUpdateAccountSummaryId}/categorySummaries
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateCategorySummary"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.macOSSoftwareUpdateCategorySummary",
    "id": "9d515d42-5d42-9d51-425d-519d425d519d",
    "displayName": "String",
    "deviceId": "String",
    "userId": "String",
    "updateCategory": "String",
    "successfulUpdateCount": "Integer",
    "failedUpdateCount": "Integer",
    "totalUpdateCount": "Integer",
    "lastUpdatedDateTime": "String (timestamp)"
  }
}
```

