---
title: "Update columns"
description: "Update the properties of a columns object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update columns
Namespace: microsoft.graph

Update the properties of a columns object.

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
PATCH /sites/{sitesId}/columns
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [columnDefinition](../resources/columndefinition.md) object.

The following table shows the properties that are required when you create the [columnDefinition](../resources/columndefinition.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|boolean|[booleanColumn](../resources/booleancolumn.md)|**TODO: Add Description**|
|calculated|[calculatedColumn](../resources/calculatedcolumn.md)|**TODO: Add Description**|
|choice|[choiceColumn](../resources/choicecolumn.md)|**TODO: Add Description**|
|columnGroup|String|**TODO: Add Description**|
|currency|[currencyColumn](../resources/currencycolumn.md)|**TODO: Add Description**|
|dateTime|[dateTimeColumn](../resources/datetimecolumn.md)|**TODO: Add Description**|
|defaultValue|[defaultColumnValue](../resources/defaultcolumnvalue.md)|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|enforceUniqueValues|Boolean|**TODO: Add Description**|
|geolocation|[geolocationColumn](../resources/geolocationcolumn.md)|**TODO: Add Description**|
|hidden|Boolean|**TODO: Add Description**|
|indexed|Boolean|**TODO: Add Description**|
|lookup|[lookupColumn](../resources/lookupcolumn.md)|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|number|[numberColumn](../resources/numbercolumn.md)|**TODO: Add Description**|
|personOrGroup|[personOrGroupColumn](../resources/personorgroupcolumn.md)|**TODO: Add Description**|
|readOnly|Boolean|**TODO: Add Description**|
|required|Boolean|**TODO: Add Description**|
|text|[textColumn](../resources/textcolumn.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [columnDefinition](../resources/columndefinition.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_columns"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/sites/{sitesId}/columns
Content-Type: application/json
Content-length: 1143

{
  "@odata.type": "#microsoft.graph.columnDefinition",
  "boolean": {
    "@odata.type": "microsoft.graph.booleanColumn"
  },
  "calculated": {
    "@odata.type": "microsoft.graph.calculatedColumn"
  },
  "choice": {
    "@odata.type": "microsoft.graph.choiceColumn"
  },
  "columnGroup": "String",
  "currency": {
    "@odata.type": "microsoft.graph.currencyColumn"
  },
  "dateTime": {
    "@odata.type": "microsoft.graph.dateTimeColumn"
  },
  "defaultValue": {
    "@odata.type": "microsoft.graph.defaultColumnValue"
  },
  "description": "String",
  "displayName": "String",
  "enforceUniqueValues": "Boolean",
  "geolocation": {
    "@odata.type": "microsoft.graph.geolocationColumn"
  },
  "hidden": "Boolean",
  "indexed": "Boolean",
  "lookup": {
    "@odata.type": "microsoft.graph.lookupColumn"
  },
  "name": "String",
  "number": {
    "@odata.type": "microsoft.graph.numberColumn"
  },
  "personOrGroup": {
    "@odata.type": "microsoft.graph.personOrGroupColumn"
  },
  "readOnly": "Boolean",
  "required": "Boolean",
  "text": {
    "@odata.type": "microsoft.graph.textColumn"
  }
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
  "@odata.type": "#microsoft.graph.columnDefinition",
  "id": "e02678f3-78f3-e026-f378-26e0f37826e0",
  "boolean": {
    "@odata.type": "microsoft.graph.booleanColumn"
  },
  "calculated": {
    "@odata.type": "microsoft.graph.calculatedColumn"
  },
  "choice": {
    "@odata.type": "microsoft.graph.choiceColumn"
  },
  "columnGroup": "String",
  "currency": {
    "@odata.type": "microsoft.graph.currencyColumn"
  },
  "dateTime": {
    "@odata.type": "microsoft.graph.dateTimeColumn"
  },
  "defaultValue": {
    "@odata.type": "microsoft.graph.defaultColumnValue"
  },
  "description": "String",
  "displayName": "String",
  "enforceUniqueValues": "Boolean",
  "geolocation": {
    "@odata.type": "microsoft.graph.geolocationColumn"
  },
  "hidden": "Boolean",
  "indexed": "Boolean",
  "lookup": {
    "@odata.type": "microsoft.graph.lookupColumn"
  },
  "name": "String",
  "number": {
    "@odata.type": "microsoft.graph.numberColumn"
  },
  "personOrGroup": {
    "@odata.type": "microsoft.graph.personOrGroupColumn"
  },
  "readOnly": "Boolean",
  "required": "Boolean",
  "text": {
    "@odata.type": "microsoft.graph.textColumn"
  }
}
```

