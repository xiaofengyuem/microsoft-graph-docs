---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var userSources = await graphClient.Compliance.Ediscovery.Cases["c816dd6f-5af8-40c5-a760-331361e05c60"].LegalHolds["277107ff-fee3-41a0-a665-a9d7f6c4824f"].UserSources
	.Request()
	.GetAsync();

```