---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printTaskDefinition = await graphClient.Print.TaskDefinitions["{printTaskDefinitionId}"]
	.Request()
	.GetAsync();

```