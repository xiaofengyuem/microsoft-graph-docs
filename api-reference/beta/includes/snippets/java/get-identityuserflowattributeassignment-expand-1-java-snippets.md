---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IIdentityUserFlowAttributeAssignmentCollectionPage userAttributeAssignments = graphClient.identity().b2cUserFlows("{id}").userAttributeAssignments()
	.buildRequest()
	.expand("userAttribute")
	.get();

```