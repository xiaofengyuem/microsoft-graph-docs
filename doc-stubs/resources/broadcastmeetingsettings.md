---
title: "broadcastMeetingSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# broadcastMeetingSettings resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAudience|broadcastMeetingAudience|**TODO: Add Description**. Possible values are: `roleIsAttendee`, `organization`, `everyone`, `unknownFutureValue`.|
|isAttendeeReportEnabled|Boolean|**TODO: Add Description**|
|isQuestionAndAnswerEnabled|Boolean|**TODO: Add Description**|
|isRecordingEnabled|Boolean|**TODO: Add Description**|
|isVideoOnDemandEnabled|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.broadcastMeetingSettings"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.broadcastMeetingSettings",
  "allowedAudience": "String",
  "isRecordingEnabled": "Boolean",
  "isVideoOnDemandEnabled": "Boolean",
  "isQuestionAndAnswerEnabled": "Boolean",
  "isAttendeeReportEnabled": "Boolean"
}
```

