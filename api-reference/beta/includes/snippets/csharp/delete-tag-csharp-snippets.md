---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var queryOptions = new List<QueryOption>()
{
	new QueryOption("forcedelete", "true")
};

await graphClient.Compliance.Ediscovery.Cases["47746044-fd0b-4a30-acfc-5272b691ba5b"].Tags["9985bd266f2f459cbebc81522734b452"]
	.Request( queryOptions )
	.DeleteAsync();

```