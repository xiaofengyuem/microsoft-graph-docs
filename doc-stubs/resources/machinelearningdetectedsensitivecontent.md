---
title: "machineLearningDetectedSensitiveContent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# machineLearningDetectedSensitiveContent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [detectedSensitiveContent](../resources/detectedsensitivecontent.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|classificationAttributes|[classificationAttribute](../resources/classificationattribute.md) collection|**TODO: Add Description** Inherited from [detectedSensitiveContent](../resources/detectedsensitivecontent.md)|
|classificationMethod|classificationMethod|**TODO: Add Description** Inherited from [detectedSensitiveContent](../resources/detectedsensitivecontent.md). Possible values are: `patternMatch`, `exactDataMatch`, `fingerprint`, `machineLearning`.|
|confidence|Int32|**TODO: Add Description** Inherited from [detectedSensitiveContentBase](../resources/detectedsensitivecontentbase.md)|
|displayName|String|**TODO: Add Description** Inherited from [detectedSensitiveContentBase](../resources/detectedsensitivecontentbase.md)|
|id|Guid|**TODO: Add Description** Inherited from [detectedSensitiveContentBase](../resources/detectedsensitivecontentbase.md)|
|matches|[sensitiveContentLocation](../resources/sensitivecontentlocation.md) collection|**TODO: Add Description** Inherited from [detectedSensitiveContent](../resources/detectedsensitivecontent.md)|
|matchTolerance|mlClassificationMatchTolerance|**TODO: Add Description**. Possible values are: `exact`, `near`.|
|modelVersion|String|**TODO: Add Description**|
|recommendedConfidence|Int32|**TODO: Add Description** Inherited from [detectedSensitiveContentBase](../resources/detectedsensitivecontentbase.md)|
|scope|sensitiveTypeScope|**TODO: Add Description** Inherited from [detectedSensitiveContent](../resources/detectedsensitivecontent.md). Possible values are: `fullDocument`, `partialDocument`.|
|sensitiveTypeSource|sensitiveTypeSource|**TODO: Add Description** Inherited from [detectedSensitiveContent](../resources/detectedsensitivecontent.md). Possible values are: `outOfBox`, `tenant`.|
|uniqueCount|Int32|**TODO: Add Description** Inherited from [detectedSensitiveContentBase](../resources/detectedsensitivecontentbase.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.machineLearningDetectedSensitiveContent"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.machineLearningDetectedSensitiveContent",
  "id": "String (identifier)",
  "displayName": "String",
  "uniqueCount": "Integer",
  "confidence": "Integer",
  "recommendedConfidence": "Integer",
  "matches": [
    {
      "@odata.type": "microsoft.graph.sensitiveContentLocation"
    }
  ],
  "scope": "String",
  "classificationAttributes": [
    {
      "@odata.type": "microsoft.graph.classificationAttribute"
    }
  ],
  "classificationMethod": "String",
  "sensitiveTypeSource": "String",
  "modelVersion": "String",
  "matchTolerance": "String"
}
```

