---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var custodianSources = await graphClient.Compliance.Ediscovery.Cases["{caseId}"].SourceCollections["{sourceCollectionId}"].CustodianSources
	.Request()
	.GetAsync();

```