---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var legalHold = await graphClient.Compliance.Ediscovery.Cases["{caseId}"].LegalHolds["{legalholdId}"]
	.Request()
	.GetAsync();

```