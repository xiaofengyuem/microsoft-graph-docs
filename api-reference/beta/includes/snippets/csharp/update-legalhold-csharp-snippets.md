---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var legalHold = new Microsoft.Graph.Ediscovery.LegalHold
{
	Description = "This is a description for a legalHold"
};

await graphClient.Compliance.Ediscovery.Cases["{caseId}"].LegalHolds["{legalholdId}"]
	.Request()
	.UpdateAsync(legalHold);

```