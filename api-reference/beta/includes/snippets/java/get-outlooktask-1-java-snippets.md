---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

OutlookTask outlookTask = graphClient.me().outlook().tasks("AAMkADA1MTrgAAA=")
	.buildRequest()
	.get();

```