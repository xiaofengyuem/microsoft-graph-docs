---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var sourceCollection = new Microsoft.Graph.Ediscovery.SourceCollection
{
	Id = "1a9b4145d8f84e39bc45a7f68c5c5119"
};

var additionalData = Microsoft.Graph.Ediscovery.DataCollectionScope.LinkedFiles;

await graphClient.Compliance.Ediscovery.Cases["080e8cad-f21f-4452-8826-0ddf7e949fdd"].ReviewSets["6fe25d32-8167-4625-b75c-c4181ccbd9d5"]
	.AddToReviewSet(sourceCollection,additionalData)
	.Request()
	.PostAsync();

```