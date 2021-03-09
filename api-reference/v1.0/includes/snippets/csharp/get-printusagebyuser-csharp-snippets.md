---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printUsageByUser = await graphClient.Reports.DailyPrintUsageByUser["{id}"]
	.Request()
	.GetAsync();

```