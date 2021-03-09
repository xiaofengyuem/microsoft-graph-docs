---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.IdentityGovernance.TermsOfUse.Agreements["{id}"]
	.Request()
	.DeleteAsync();

```