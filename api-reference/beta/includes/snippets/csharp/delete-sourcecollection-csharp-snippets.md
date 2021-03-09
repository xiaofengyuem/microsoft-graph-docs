---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Compliance.Ediscovery.Cases["{caseId}"].SourceCollections["{sourceCollectionId}"]
	.Request()
	.DeleteAsync();

```