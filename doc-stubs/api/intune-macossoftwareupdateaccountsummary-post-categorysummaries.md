---
title: "Create categorySummaries"
description: "Create a new macOSSoftwareUpdateCategorySummary object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create categorySummaries
Namespace: microsoft.graph

Create a new macOSSoftwareUpdateCategorySummary object.

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
POST /deviceManagement/macOSSoftwareUpdateAccountSummaries/{macOSSoftwareUpdateAccountSummaryId}/categorySummaries
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object.

The following table shows the properties that are required when you create the [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|deviceId|String|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|updateCategory|macOSSoftwareUpdateCategory|**TODO: Add Description**. Possible values are: `critical`, `configurationDataFile`, `firmware`, `other`.|
|successfulUpdateCount|Int32|**TODO: Add Description**|
|failedUpdateCount|Int32|**TODO: Add Description**|
|totalUpdateCount|Int32|**TODO: Add Description**|
|lastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [macOSSoftwareUpdateCategorySummary](../resources/intune-macossoftwareupdatecategorysummary.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_macossoftwareupdatecategorysummary_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/deviceManagement/macOSSoftwareUpdateAccountSummaries/{macOSSoftwareUpdateAccountSummaryId}/categorySummaries
Content-Type: application/json
Content-length: 339

{
  "@odata.type": "#microsoft.graph.macOSSoftwareUpdateCategorySummary",
  "displayName": "String",
  "deviceId": "String",
  "userId": "String",
  "updateCategory": "String",
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
  "@odata.type": "microsoft.graph.macOSSoftwareUpdateCategorySummary"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
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
```

