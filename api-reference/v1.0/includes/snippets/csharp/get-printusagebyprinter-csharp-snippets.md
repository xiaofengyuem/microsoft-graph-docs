---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printUsageByPrinter = await graphClient.Reports.DailyPrintUsageByPrinter["{id}"]
	.Request()
	.GetAsync();

```