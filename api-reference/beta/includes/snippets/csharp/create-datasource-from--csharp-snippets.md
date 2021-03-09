---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var dataSource = new UserSource
{
	Email = "badguy@contoso.com"
};

await graphClient.Compliance.Ediscovery.Cases["{caseId}"].SourceCollections["{sourceCollectionId}"].AdditionalSources
	.Request()
	.AddAsync(dataSource);

```