---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printServiceEndpoint = await graphClient.Print.Services["{printServiceId}"].Endpoints["{printServiceEndpointId}"]
	.Request()
	.GetAsync();

```