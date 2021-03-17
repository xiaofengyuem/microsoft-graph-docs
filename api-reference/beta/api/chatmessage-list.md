---
title: "List messages in a channel or a chat"
description: "List messages in a channel (without the replies) or a chat"
localization_priority: Priority
author: "RamjotSingh"
ms.prod: "microsoft-teams"
doc_type: apiPageType
---

# List messages in a channel or a chat

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Retrieve the list of [messages](../resources/chatmessage.md) (without the replies) in a [channel](../resources/channel.md) or a [chat](../resources/chat.md). 

To get the replies for a message, call the [list message replies](channel-list-messagereplies.md) or the [get message reply](channel-get-messagereply.md) API. 

> **Note**: This API supports subscribing to changes (create, update, and delete) using [change notifications](../resources/webhooks.md). This allows callers to subscribe and get changes in real time. For details, see [Get notifications for messages](/graph/teams-changenotifications-chatmessage).

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

### Permissions for channel

| Permission type                        | Permissions (from least to most privileged) |
|:---------------------------------------|:--------------------------------------------|
|Delegated (work or school account)| ChannelMessage.Read.All, Group.Read.All, Group.Read.WriteAll |
|Delegated (personal Microsoft account)|Not supported.|
|Application| ChannelMessage.Read.Group*, ChannelMessage.Read.All, Group.Read.All, Group.ReadWrite.All |

### Permissions for chat

| Permission type                        | Permissions (from least to most privileged) |
|:---------------------------------------|:--------------------------------------------|
|Delegated (work or school account)| Chat.Read, Chat.ReadWrite|
|Delegated (personal Microsoft account)|Not supported.|
|Application| Chat.Read.All, Chat.ReadWrite.All|

> **Note**: Permissions marked with * use [resource-specific consent]( https://aka.ms/teams-rsc).

> [!NOTE]
> Before calling this API with application permissions, you must request access. For details, see [Protected APIs in Microsoft Teams](/graph/teams-protected-apis).

## HTTP request

### Get messages in a channel
<!-- { "blockType": "ignored" } -->
```http
GET /teams/{team-id}/channels/{channel-id}/messages
```

### Get messages in a chat
<!-- { "blockType": "ignored" } -->
```http
GET /chats/{chat-id}/messages
GET /users/{user-id}/chats/{chat-id}/messages
GET /me/chats/{chat-id}/messages
```

## Optional query parameters

You can use the [$top](/graph/query-parameters#top-parameter) query parameter to control the number of items per response. 
The other [OData query parameters](/graph/query-parameters) are not currently supported.

> **Note:** [GET /teams/{team-id}/channels/{channel-id}/messages/delta](chatmessage-delta.md) supports filtering by date, which provides similar data to GET /teams/{team-id}/channels/{channel-id}/messages.

## Request headers

| Header       | Value |
|:---------------|:--------|
| Authorization  | Bearer {token}. Required.  |

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [chatMessage](../resources/chatmessage.md) objects in the response body.

## Examples

### Example 1 : Retrieve messages in a channel

### Request

The following is an example of the request.

```http
GET https://graph.microsoft.com/beta/teams/fbe2bf47-16c8-47cf-b4a5-4b9b187c508b/channels/19:4a95f7d8db4c4e7fae857bcebe0623e6@thread.tacv2/messages
```

### Response

The following is an example of the response.

> [!NOTE]
> The response object shown here might be shortened for readability. All the properties will be returned from an actual call.

<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.chatMessage",
  "isCollection": true
} -->

```http
HTTP/1.1 200 OK
Content-type: application/json

{
    "@odata.context": "https://graph.microsoft.com/beta/$metadata#teams('fbe2bf47-16c8-47cf-b4a5-4b9b187c508b')/channels('19%3A4a95f7d8db4c4e7fae857bcebe0623e6%40thread.tacv2')/messages",
    "@odata.count": 20,
    "@odata.nextLink": "https://graph.microsoft.com/beta/teams/fbe2bf47-16c8-47cf-b4a5-4b9b187c508b/channels/19:4a95f7d8db4c4e7fae857bcebe0623e6@thread.tacv2/messages?$skiptoken=%5b%7B%22token%22%3a%22%2bRID%3a~vpsQAJ9uAC2f7QwAAACcBQ%3d%3d%23RT%3a1%23TRC%3a20%23RTD%3aAyAER1ygxSHVHGAn2S99BTI6OzViOjZnOGU5ZWM1ZDVmOGdiZjk2OGNkZmNmMTczNGY3QXVpc2ZiZS91YmR3MzwyNzIyNDY2ODU1MjI3AA%3d%3d%23ISV%3a2%23IEO%3a65551%23QCF%3a3%23FPC%3aAggEAAAAcBYAABUFAADQKgAABAAAAHAWAAACALu4GwAAAHAWAAACAPSTMwAAAHAWAACaAFWa84BXgQKAEIAMgBaAE4AUgAuAAoAIwAIgACAAAiAACAABACCAAAEVgBSAI4AYgA%2bAGQAEEAAQAAEABACAAAIEEBBAACAYgB%2bAH4AbgBqACoAHwAICCBAEEIAAAgEQAACAIoAZgB2ADoAMgAKAPoAZgB2AJoAXgBIAgiAAQUqLF4AJgALACARAgBCACoAfgB6AIwABgYCQAAFXAAAAcBYAAAYA%2f50ZgGeEXwAAAHAWAAAEAPaBS4V7AAAAcBYAAAIA1aSJAAAAcBYAAAIAtLmbAAAAcBYAAAIAqKU5AAAA0CoAAAYA6pF7iYOBaQIAANAqAAAcAEUPAMAAMAACAQCBAHQAADDAgCAAQgByAQAzUJDRBAAA0CoAAAQAETwKAA4FAADQKgAAAgBekRUFAADQKgAAHAB2pQCABYAMgJeAH4ATgAGAvIIIgASABIAFgCWA%22%2c%22range%22%3a%7B%22min%22%3a%2205C1D79B33ADE4%22%2c%22max%22%3a%2205C1D7A52F89EC%22%7D%7D%5d",
    "value": [
        {
            "id": "1614618259349",
            "replyToId": null,
            "etag": "1614618259349",
            "messageType": "message",
            "createdDateTime": "2021-03-01T17:04:19.349Z",
            "lastModifiedDateTime": "2021-03-01T17:04:19.349Z",
            "lastEditedDateTime": null,
            "deletedDateTime": null,
            "subject": null,
            "summary": null,
            "chatId": null,
            "importance": "normal",
            "locale": "en-us",
            "webUrl": "https://teams.microsoft.com/l/message/19%3A4a95f7d8db4c4e7fae857bcebe0623e6%40thread.tacv2/1614618259349?groupId=fbe2bf47-16c8-47cf-b4a5-4b9b187c508b&tenantId=2432b57b-0abd-43db-aa7b-16eadd115d34&createdTime=1614618259349&parentMessageId=1614618259349",
            "policyViolation": null,
            "from": {
                "application": null,
                "device": null,
                "conversation": null,
                "user": {
                    "id": "8ea0e38b-efb3-4757-924a-5f94061cf8c2",
                    "displayName": "Ramjot Singh",
                    "userIdentityType": "aadUser"
                }
            },
            "body": {
                "contentType": "html",
                "content": "<div><div><div><span><img height=\"250\" src=\"https://graph.microsoft.com/beta/teams/fbe2bf47-16c8-47cf-b4a5-4b9b187c508b/channels/19:4a95f7d8db4c4e7fae857bcebe0623e6@thread.tacv2/messages/1614618259349/hostedContents/aWQ9eF8wLXd1cy1kOS1jZTI3NDkxOTIzMTJjYWI5NDczMWQwYTgzNTFjN2VhNSx0eXBlPTEsdXJsPWh0dHBzOi8vdXMtYXBpLmFzbS5za3lwZS5jb20vdjEvb2JqZWN0cy8wLXd1cy1kOS1jZTI3NDkxOTIzMTJjYWI5NDczMWQwYTgzNTFjN2VhNS92aWV3cy9pbWdv/$value\" width=\"424.6575342465753\" style=\"vertical-align:bottom; width:424px; height:250px\"></span></div></div></div>"
            },
            "channelIdentity": {
                "teamId": "fbe2bf47-16c8-47cf-b4a5-4b9b187c508b",
                "channelId": "19:4a95f7d8db4c4e7fae857bcebe0623e6@thread.tacv2"
            },
            "attachments": [],
            "mentions": [],
            "reactions": []
        },
        {
            "id": "1614029151240",
            "replyToId": null,
            "etag": "1614029151240",
            "messageType": "message",
            "createdDateTime": "2021-02-22T21:25:51.24Z",
            "lastModifiedDateTime": "2021-02-22T21:25:51.24Z",
            "lastEditedDateTime": null,
            "deletedDateTime": "2021-02-22T21:25:51.24Z",
            "subject": null,
            "summary": null,
            "chatId": null,
            "importance": "normal",
            "locale": "en-us",
            "webUrl": "https://teams.microsoft.com/l/message/19%3A4a95f7d8db4c4e7fae857bcebe0623e6%40thread.tacv2/1614029151240?groupId=fbe2bf47-16c8-47cf-b4a5-4b9b187c508b&tenantId=2432b57b-0abd-43db-aa7b-16eadd115d34&createdTime=1614029151240&parentMessageId=1614029151240",
            "from": null,
            "policyViolation": null,
            "body": {
                "contentType": "text",
                "content": null
            },
            "channelIdentity": {
                "teamId": "fbe2bf47-16c8-47cf-b4a5-4b9b187c508b",
                "channelId": "19:4a95f7d8db4c4e7fae857bcebe0623e6@thread.tacv2"
            },
            "attachments": [],
            "mentions": [],
            "reactions": []
        }
    ]
}
```

### Example 2 : Retrieve messages in a chat

### Request

The following is an example of the request.

```http
GET https://graph.microsoft.com/beta/chats/19:2da4c29f6d7041eca70b638b43d45437@thread.v2/messages
```

### Response

The following is an example of the response.

> [!NOTE]
> The response object shown here might be shortened for readability. All the properties will be returned from an actual call.

<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.chatMessage",
  "isCollection": true
} -->

```http
{
    "@odata.context": "https://graph.microsoft.com/beta/$metadata#chats('19%3A2da4c29f6d7041eca70b638b43d45437%40thread.v2')/messages",
    "@odata.count": 3,
    "@odata.nextLink": "https://graph.microsoft.com/beta/chats/19:2da4c29f6d7041eca70b638b43d45437@thread.v2/messages?$skiptoken=M2UyZDAwMDAwMDMxMzkzYTMyNjQ2MTM0NjMzMjM5NjYzNjY0MzczMDM0MzE2NTYzNjEzNzMwNjIzNjMzMzg2MjM0MzM2NDM0MzUzNDMzMzc0MDc0Njg3MjY1NjE2NDJlNzYzMjAxMDEwMDAwMDAwMDAwMDAwMDMxMjRiYzNkNzgwMTAwMDB8MTYxNTk0MzQ0MzUwNQ%3d%3d",
    "value": [
        {
            "id": "1602607513377",
            "replyToId": null,
            "etag": "1615943443505",
            "messageType": "message",
            "createdDateTime": "2020-10-13T16:45:13.377Z",
            "lastModifiedDateTime": "2021-03-17T01:10:43.505Z",
            "lastEditedDateTime": "2021-03-17T01:10:43.505Z",
            "deletedDateTime": null,
            "subject": null,
            "summary": null,
            "chatId": "19:2da4c29f6d7041eca70b638b43d45437@thread.v2",
            "importance": "normal",
            "locale": "en-us",
            "webUrl": null,
            "channelIdentity": null,
            "policyViolation": null,
            "from": {
                "application": null,
                "device": null,
                "conversation": null,
                "user": {
                    "id": "8ea0e38b-efb3-4757-924a-5f94061cf8c2",
                    "displayName": "Ramjot Singh",
                    "userIdentityType": "aadUser"
                }
            },
            "body": {
                "contentType": "text",
                "content": "Added a new tab at the top of this chat."
            },
            "attachments": [],
            "mentions": [],
            "reactions": []
        },
        {
            "id": "1595558258253",
            "replyToId": null,
            "etag": "1595558258253",
            "messageType": "message",
            "createdDateTime": "2020-07-24T02:37:38.253Z",
            "lastModifiedDateTime": "2020-07-24T02:37:38.253Z",
            "lastEditedDateTime": null,
            "deletedDateTime": null,
            "subject": null,
            "summary": null,
            "chatId": "19:2da4c29f6d7041eca70b638b43d45437@thread.v2",
            "importance": "normal",
            "locale": "en-us",
            "webUrl": null,
            "channelIdentity": null,
            "policyViolation": null,
            "from": {
                "application": null,
                "device": null,
                "conversation": null,
                "user": {
                    "id": "8ea0e38b-efb3-4757-924a-5f94061cf8c2",
                    "displayName": "Ramjot Singh",
                    "userIdentityType": "aadUser"
                }
            },
            "body": {
                "contentType": "html",
                "content": "<div>Added a new tab at the top of this chat. Here's a link.</div><attachment id=\"tab::90dd9b6f-a710-40be-bb7c-a56e0b1807de\"></attachment>"
            },
            "attachments": [
                {
                    "id": "tab::90dd9b6f-a710-40be-bb7c-a56e0b1807de",
                    "contentType": "tabReference",
                    "contentUrl": null,
                    "content": null,
                    "name": "Bing",
                    "thumbnailUrl": null
                }
            ],
            "mentions": [],
            "reactions": []
        },
        {
            "id": "1595558052222",
            "replyToId": null,
            "etag": "1595558052222",
            "messageType": "message",
            "createdDateTime": "2020-07-24T02:34:12.222Z",
            "lastModifiedDateTime": "2020-07-24T02:34:12.222Z",
            "lastEditedDateTime": null,
            "deletedDateTime": null,
            "subject": null,
            "summary": null,
            "chatId": "19:2da4c29f6d7041eca70b638b43d45437@thread.v2",
            "importance": "normal",
            "locale": "en-us",
            "webUrl": null,
            "channelIdentity": null,
            "policyViolation": null,
            "from": {
                "application": null,
                "device": null,
                "conversation": null,
                "user": {
                    "id": "8ea0e38b-efb3-4757-924a-5f94061cf8c2",
                    "displayName": "Ramjot Singh",
                    "userIdentityType": "aadUser"
                }
            },
            "body": {
                "contentType": "text",
                "content": "GroupChatTest"
            },
            "attachments": [],
            "mentions": [],
            "reactions": []
        }
    ]
}
```

## See also

- [Get message in a channel or a chat](chatmessage-get.md)
- [Send message in a channel or a chat](chatmessage-post.md)

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "List messages in a channel (without the replies) or a chat",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
  ]
}
-->

