---
title: "List windows10XSCEPCertificateProfile"
description: "Get a list of the windows10XSCEPCertificateProfile objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List windows10XSCEPCertificateProfile
Namespace: microsoft.graph

Get a list of the [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) objects and their properties.

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
GET ** Collection URI for microsoft.graph.windows10XSCEPCertificateProfile not found
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

If successful, this method returns a `200 OK` response code and a collection of [windows10XSCEPCertificateProfile](../resources/windows10xscepcertificateprofile.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_windows10xscepcertificateprofile"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for microsoft.graph.windows10XSCEPCertificateProfile not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.windows10XSCEPCertificateProfile)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.windows10XSCEPCertificateProfile",
      "id": "5c107d57-7d57-5c10-577d-105c577d105c",
      "version": "Integer",
      "displayName": "String",
      "description": "String",
      "creationDateTime": "String (timestamp)",
      "lastModifiedDateTime": "String (timestamp)",
      "roleScopeTagIds": [
        "String"
      ],
      "certificateStore": "String",
      "certificateValidityPeriodScale": "String",
      "certificateValidityPeriodValue": "Integer",
      "extendedKeyUsages": [
        {
          "@odata.type": "microsoft.graph.extendedKeyUsage"
        }
      ],
      "hashAlgorithm": [
        "String"
      ],
      "keySize": "String",
      "keyStorageProvider": "String",
      "keyUsage": "String",
      "renewalThresholdPercentage": "Integer",
      "rootCertificateId": "Guid",
      "scepServerUrls": [
        "String"
      ],
      "subjectAlternativeNameFormats": [
        {
          "@odata.type": "microsoft.graph.windows10XCustomSubjectAlternativeName"
        }
      ],
      "subjectNameFormatString": "String"
    }
  ]
}
```

