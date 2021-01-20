---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

Content members = graphClient.me().chats().{id}().members()
	.buildRequest()
	.get();

```