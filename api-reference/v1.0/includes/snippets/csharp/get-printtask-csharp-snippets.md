---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printTask = await graphClient.Print.TaskDefinitions["{taskDefinitionId}"].Tasks["{taskId}"]
	.Request()
	.GetAsync();

```