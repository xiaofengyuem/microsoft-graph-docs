---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var @string = await graphClient.Compliance.Ediscovery.Cases["99e865fc-e29f-479a-ba83-9e58eb017103"].Operations["63926d4779c243458902328d83f61f53"]
	.GetDownloadUrl()
	.Request()
	.GetAsync();

```