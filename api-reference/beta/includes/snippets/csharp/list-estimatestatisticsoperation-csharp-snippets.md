---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var estimateStatisticsOperation = await graphClient.Compliance.Ediscovery.Cases["{caseId}"].SourceCollections["95bdbf84f02f4bdaafbbb2fe945a4962"].LastEstimateStatisticsOperation
	.Request()
	.GetAsync();

```