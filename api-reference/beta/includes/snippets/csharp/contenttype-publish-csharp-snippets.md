---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Sites["{siteId}"].ContentTypes["{contentTypeId}"]
	.Publish()
	.Request()
	.PostAsync();

```