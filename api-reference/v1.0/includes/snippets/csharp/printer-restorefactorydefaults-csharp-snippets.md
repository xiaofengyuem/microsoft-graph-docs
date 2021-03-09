---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Print.Printers["{printerId}"]
	.RestoreFactoryDefaults()
	.Request()
	.PostAsync();

```