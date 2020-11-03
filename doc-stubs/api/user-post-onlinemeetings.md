---
title: "Create onlineMeetings"
description: "Create a new onlineMeeting object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create onlineMeetings
Namespace: microsoft.graph

Create a new onlineMeeting object.

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
POST /me/onlineMeetings
POST /app/onlineMeetings
POST /communications/onlineMeetings
POST /users/{usersId}/onlineMeetings
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [onlineMeeting](../resources/onlinemeeting.md) object.

The following table shows the properties that are required when you create the [onlineMeeting](../resources/onlinemeeting.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|creationDateTime|DateTimeOffset|**TODO: Add Description**|
|startDateTime|DateTimeOffset|**TODO: Add Description**|
|endDateTime|DateTimeOffset|**TODO: Add Description**|
|canceledDateTime|DateTimeOffset|**TODO: Add Description**|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|
|entryExitAnnouncement|Boolean|**TODO: Add Description**|
|joinUrl|String|**TODO: Add Description**|
|subject|String|**TODO: Add Description**|
|isCancelled|Boolean|**TODO: Add Description**|
|participants|[meetingParticipants](../resources/meetingparticipants.md)|**TODO: Add Description**|
|isBroadcast|Boolean|**TODO: Add Description**|
|accessLevel|accessLevel|**TODO: Add Description**. Possible values are: `everyone`, `invited`, `locked`, `sameEnterprise`, `sameEnterpriseAndFederated`.|
|capabilities|meetingCapabilities collection|**TODO: Add Description**. Possible values are: `questionAndAnswer`, `unknownFutureValue`.|
|audioConferencing|[audioConferencing](../resources/audioconferencing.md)|**TODO: Add Description**|
|chatInfo|[chatInfo](../resources/chatinfo.md)|**TODO: Add Description**|
|videoTeleconferenceId|String|**TODO: Add Description**|
|externalId|String|**TODO: Add Description**|
|joinInformation|[itemBody](../resources/itembody.md)|**TODO: Add Description**|
|lobbyBypassSettings|[lobbyBypassSettings](../resources/lobbybypasssettings.md)|**TODO: Add Description**|
|isEntryExitAnnounced|Boolean|**TODO: Add Description**|
|allowedPresenters|onlineMeetingPresenters|**TODO: Add Description**. Possible values are: `everyone`, `organization`, `roleIsPresenter`, `organizer`, `unknownFutureValue`.|



## Response

If successful, this method returns a `201 Created` response code and an [onlineMeeting](../resources/onlinemeeting.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_onlinemeeting_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/me/onlineMeetings
Content-Type: application/json
Content-length: 1037

{
  "@odata.type": "#microsoft.graph.onlineMeeting",
  "creationDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "endDateTime": "String (timestamp)",
  "canceledDateTime": "String (timestamp)",
  "expirationDateTime": "String (timestamp)",
  "entryExitAnnouncement": "Boolean",
  "joinUrl": "String",
  "subject": "String",
  "isCancelled": "Boolean",
  "participants": {
    "@odata.type": "microsoft.graph.meetingParticipants"
  },
  "isBroadcast": "Boolean",
  "accessLevel": "String",
  "capabilities": [
    "String"
  ],
  "audioConferencing": {
    "@odata.type": "microsoft.graph.audioConferencing"
  },
  "chatInfo": {
    "@odata.type": "microsoft.graph.chatInfo"
  },
  "videoTeleconferenceId": "String",
  "externalId": "String",
  "joinInformation": {
    "@odata.type": "microsoft.graph.itemBody"
  },
  "lobbyBypassSettings": {
    "@odata.type": "microsoft.graph.lobbyBypassSettings"
  },
  "isEntryExitAnnounced": "Boolean",
  "allowedPresenters": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.onlineMeeting"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.onlineMeeting",
  "id": "1ba9d9da-d9da-1ba9-dad9-a91bdad9a91b",
  "creationDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "endDateTime": "String (timestamp)",
  "canceledDateTime": "String (timestamp)",
  "expirationDateTime": "String (timestamp)",
  "entryExitAnnouncement": "Boolean",
  "joinUrl": "String",
  "subject": "String",
  "isCancelled": "Boolean",
  "participants": {
    "@odata.type": "microsoft.graph.meetingParticipants"
  },
  "isBroadcast": "Boolean",
  "accessLevel": "String",
  "capabilities": [
    "String"
  ],
  "audioConferencing": {
    "@odata.type": "microsoft.graph.audioConferencing"
  },
  "chatInfo": {
    "@odata.type": "microsoft.graph.chatInfo"
  },
  "videoTeleconferenceId": "String",
  "externalId": "String",
  "joinInformation": {
    "@odata.type": "microsoft.graph.itemBody"
  },
  "lobbyBypassSettings": {
    "@odata.type": "microsoft.graph.lobbyBypassSettings"
  },
  "isEntryExitAnnounced": "Boolean",
  "allowedPresenters": "String"
}
```

