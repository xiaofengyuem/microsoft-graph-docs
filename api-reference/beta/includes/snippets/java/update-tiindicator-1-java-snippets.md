---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

TiIndicator tiIndicator = new TiIndicator();
tiIndicator.description = "description-updated";

graphClient.security().tiIndicators("{id}")
	.buildRequest()
	.patch(tiIndicator);

```