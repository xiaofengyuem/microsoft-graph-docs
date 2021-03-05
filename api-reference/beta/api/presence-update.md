---
title: "Update presence"
description: "Update the presence information for a user's application session."
author: "elvinyang-msft"
localization_priority: Normal
doc_type: apiPageType
ms.prod: "cloud-communications"
---

# Update presence

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

### Concept: presence sessions
A user could have multiple presence sessions as the user could be on multiple Teams clients (desktop, mobile and web). Each Teams client has an independent presence session and the user's presence is an aggregated status from all the sessions underneath.

Now with [presenceSession](../resources/presencesession.md), your application can have its own presence session and be able to update the status.

### Keep alive and timeout
A presence session has a timeout of 5 minutes, so the application needs to call this API before the timeout to keep alive, even if the presence has not changed since the last call.

If times out, the presence status would fade way in stages. For example an application has updated `Available/Available` but never makes a call to keep alive, the presence session would change to `Available/AvailableInactive` with the first timeout, then `Away/Away` with the second timeout, and finally `Offline/Offline` with the third timeout.

### Delete the presence session
The application can delete its presence session. If a user's only presence session (all sessions from Teams clients and applications adding together) gets deleted, the user's presence will change to `Offline/Offline`.

## Permissions
The following permission is required to call the API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type | Permissions            |
| :-------------- | :--------------------- |
| Application     | Presence.ReadWrite.All |

## HTTP Requests
Request to update a presence session:
<!-- { "blockType": "ignored" } -->
```http
PUT /users/{userId}/presence/sessions/{sessionId}
```

Request to delete a presence session:
<!-- { "blockType": "ignored" } -->
```http
DELETE /users/{userId}/presence/sessions/{sessionId}
```

> [!IMPORTANT]
> * When accessing the application's presence session for a user, the application ID should be supplied as the `sessionId`.

## Request Headers
| Name          | Description               |
| :------------ | :------------------------ |
| Authorization | Bearer {token}. Required. |


## Request body

In the request body, provide a JSON object with the following parameters.

| Parameter    | Type   | Description                                   |
| :----------- | :----- | :-------------------------------------------- |
| availability | string | The base presence information.                |
| activity     | string | The supplemental information to availability. |

Supported combinations are:
| Value of `availability` | Value of `activity` | Description                                                            |
| :---------------------- | :------------------ | :--------------------------------------------------------------------- |
| Available               | Available           | Updates the presence session as Available.                                     |
| Busy                    | InACall             | Updates the presence session as Busy, InACall.                                 |
| Busy                    | InAConferenceCall   | Updates the presence session as Busy, InAConferenceCall.                       |
| Away                    | Away                | Updates the presence session as Away.                                          |

## Response
If successful, this method returns a `200 OK` response code.

## Examples

### Example 1: Update the application's presence session
Below example shows the application with ID `22553876-f5ab-4529-bffb-cfe50aa89f87` updating its presence session for user `fa8bf3dc-eca7-46b7-bad1-db199b62afc3`.

#### Request

# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "name": "get-your-presence"
}-->

```msgraph-interactive
PUT https://graph.microsoft.com/beta/users/fa8bf3dc-eca7-46b7-bad1-db199b62afc3/presence/22553876-f5ab-4529-bffb-cfe50aa89f87
Content-Type: application/json
{  
  "availability": "Available",
  "activity": "Available"
}
```

#### Response

<!-- {
  "blockType": "response",
  "name": "get-your-presence",
  "@odata.type": "microsoft.graph.presence",
  "truncated":"true"
} -->
```http
HTTP/1.1 200 OK
```

### Example 2: Delete the application's presence session
Below example shows the application with ID `22553876-f5ab-4529-bffb-cfe50aa89f87` deleting its presence session for user `fa8bf3dc-eca7-46b7-bad1-db199b62afc3`.

#### Request

# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "name": "get-your-presence"
}-->

```msgraph-interactive
DELETE https://graph.microsoft.com/beta/users/fa8bf3dc-eca7-46b7-bad1-db199b62afc3/presence/22553876-f5ab-4529-bffb-cfe50aa89f87
```

#### Response

<!-- {
  "blockType": "response",
  "name": "get-your-presence",
  "@odata.type": "microsoft.graph.presence",
  "truncated":"true"
} -->
```http
HTTP/1.1 200 OK
```