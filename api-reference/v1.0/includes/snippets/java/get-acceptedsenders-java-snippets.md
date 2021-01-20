---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

DirectoryObjectCollectionPage acceptedSenders = graphClient.groups("{id}").acceptedSenders()
	.buildRequest()
	.get();

```