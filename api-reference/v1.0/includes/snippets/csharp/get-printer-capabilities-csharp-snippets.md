---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printer = await graphClient.Print.Printers["{printerId}"]
	.Request()
	.Select("id,displayName,capabilities")
	.GetAsync();

```