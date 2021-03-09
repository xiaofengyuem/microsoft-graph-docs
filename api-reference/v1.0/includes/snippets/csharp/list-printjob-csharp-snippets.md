---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var jobs = await graphClient.Print.Shares["{printerShareId}"].Jobs
	.Request()
	.GetAsync();

```