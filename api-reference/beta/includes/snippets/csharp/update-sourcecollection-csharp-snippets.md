---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var sourceCollection = new Microsoft.Graph.Ediscovery.SourceCollection
{
	DisplayName = "Quarterly Financials search"
};

await graphClient.Compliance.Ediscovery.Cases["{caseId}"].SourceCollections["1a9b4145d8f84e39bc45a7f68c5c5119"]
	.Request()
	.UpdateAsync(sourceCollection);

```