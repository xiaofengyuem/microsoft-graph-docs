---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var stream = await graphClient.Print.Printers["{printerId}"].Jobs["{printJobId}"].Documents["{printDocumentId}"].Content
	.Request()
	.GetAsync();

```