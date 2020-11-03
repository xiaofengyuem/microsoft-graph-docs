---
title: "Add runSummary"
description: "Add runSummary by posting to the runSummary collection."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Add runSummary
Namespace: microsoft.graph

Add runSummary by posting to the runSummary collection.

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
POST ** Collection URI for microsoft.graph.deviceManagementScriptRunSummary not found/$ref
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [deviceManagementScriptRunSummary](../resources/intune-devicemanagementscriptrunsummary.md) object.

The following table shows the properties that are required when you create the [deviceManagementScriptRunSummary](../resources/intune-devicemanagementscriptrunsummary.md).

|Property|Type|Description|
|:---|:---|:---|
|successDeviceCount|Int32|**TODO: Add Description**|
|errorDeviceCount|Int32|**TODO: Add Description**|
|successUserCount|Int32|**TODO: Add Description**|
|errorUserCount|Int32|**TODO: Add Description**|



## Response

If successful, this method returns a `204 No Content` response code and a [deviceManagementScriptRunSummary](../resources/intune-devicemanagementscriptrunsummary.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_devicemanagementscriptrunsummary_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.deviceManagementScriptRunSummary not found/$ref
Content-Type: application/json
Content-length: 210

{
  "@odata.type": "#microsoft.graph.deviceManagementScriptRunSummary",
  "successDeviceCount": "Integer",
  "errorDeviceCount": "Integer",
  "successUserCount": "Integer",
  "errorUserCount": "Integer"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.deviceManagementScriptRunSummary"
}
-->
``` http
HTTP/1.1 204 No Content

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.deviceManagementScriptRunSummary",
  "successDeviceCount": "Integer",
  "errorDeviceCount": "Integer",
  "successUserCount": "Integer",
  "errorUserCount": "Integer"
}
```

