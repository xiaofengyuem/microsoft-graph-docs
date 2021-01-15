---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

String webUrl = "webUrl value";

graphClient.me().onenote().notebooks()
	.getNotebookFromWebUrl(NotebookGetNotebookFromWebUrlParameterSet
		.newBuilder()
		.withWebUrl(webUrl)
		.build())
	.buildRequest()
	.post();

```