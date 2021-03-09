---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var tags = await graphClient.Compliance.Ediscovery.Cases["47746044-fd0b-4a30-acfc-5272b691ba5b"].Tags
	.Request()
	.GetAsync();

```