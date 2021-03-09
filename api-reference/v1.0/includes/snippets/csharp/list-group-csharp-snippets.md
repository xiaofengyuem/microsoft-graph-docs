---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var allowedGroups = await graphClient.Print.Shares["{printerShareId}"].AllowedGroups
	.Request()
	.GetAsync();

```