---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Users["{userId}"].Profile.Notes["{id}"]
	.Request()
	.DeleteAsync();

```