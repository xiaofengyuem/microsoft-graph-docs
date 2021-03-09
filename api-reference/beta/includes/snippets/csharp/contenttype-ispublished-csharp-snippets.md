---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var boolean = await graphClient.Sites["{siteId}"].ContentTypes["{contentTypeId}"]
	.IsPublished()
	.Request()
	.GetAsync();

```