---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var sourceCollection = await graphClient.Compliance.Ediscovery.Cases["47746044-fd0b-4a30-acfc-5272b691ba5b"].SourceCollections["1a9b4145d8f84e39bc45a7f68c5c5119"]
	.Request()
	.Expand("lastEstimateStatisticsOperation")
	.GetAsync();

```