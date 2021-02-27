---
title: "Set presence"
description: "Set a the presence information for a user's app session."
author: "elvinyang-msft"
localization_priority: Normal
doc_type: apiPageType
ms.prod: "cloud-communications"
---

# Set presence

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Set the [presence](../resources/presence.md) information for a user's app session.
> [!IMPORTANT]
> * When an application calls this API to set the presence for a user, it sets the presence in the scope of the user's app session.
> * A user could have multiple presence sessions, as the user could sign in via multiple clients (desktop, mobile or web) at the same time. An app session is just like the user "signs in" with the app.
> * When the GET presence API is called, an aggregated presence of the user is returned. The returned result is aggregated from all presence sessions of the user, plus the calendar events and more.

## Keep alive and timeout
The presence of a user's app session has a timeout of 5 minutes, so the application needs to call this API before the timeout to keep alive, even if the presence has never changed.

If times out, the presence would fade way in stages. For example an application has set `Available/Available` but never makes a call to keep alive, the presence of the app session would change to `Available/AvailableInactive` with the first timeout, then `Away/Away` with the second timeout, and finally `Offline/Offline` with the third timeout.

## Permissions
The following permission is required to call the API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type | Permissions            |
| :-------------- | :--------------------- |
| Application     | Presence.ReadWrite.All |

## HTTP Requests
<!-- { "blockType": "ignored" } -->
```http
PATCH /users/{id}/presence
```

## Request Headers
| Name          | Description               |
| :------------ | :------------------------ |
| Authorization | Bearer {token}. Required. |


## Request body

In the request body, provide a JSON object with the following parameters.

| Parameter      | Type   | Description                                            |
| :------------- | :----- | :----------------------------------------------------- |
| `availability` | string | The base presence information for a user.              |
| `activity`     | string | The supplemental information to a user's availability. |

Supported combinations are:
| Value of `availability` | Value of `activity` | Description                                                            |
| :---------------------- | :------------------ | :--------------------------------------------------------------------- |
| Available               | Available           | Sets the app session as Available.                                     |
| Busy                    | InACall             | Sets the app session as Busy, InACall.                                 |
| Busy                    | InAConferenceCall   | Sets the app session as Busy, InAConferenceCall.                       |
| Away                    | Away                | Sets the app session as Away.                                          |
| Offline                 | Offline             | Sets the app session Offline, effectively "signs off" the app session. |

## Response
If successful, this method returns a `200 OK` response code.

## Examples

### Example 1: Set the presence for a user's app session.

#### Request


# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "name": "get-your-presence"
}-->

```msgraph-interactive
PATCH https://graph.microsoft.com/beta/users/fa8bf3dc-eca7-46b7-bad1-db199b62afc3/presence
Content-Type: application/json
{  
  "availability": "Available",
  "activity": "Available"
}
```

---


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
