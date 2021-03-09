---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Print.Printers["{printerId}"].Jobs["{printJobId}"]
	.Cancel()
	.Request()
	.PostAsync();

```