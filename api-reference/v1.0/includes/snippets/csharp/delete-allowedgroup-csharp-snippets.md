---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Print.Shares["{printerShareId}"].AllowedGroups["{groupId}"].Reference
	.Request()
	.DeleteAsync();

```