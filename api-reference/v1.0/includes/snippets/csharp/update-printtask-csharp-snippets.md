---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var printTask = new PrintTask
{
	Status = new PrintTaskStatus
	{
		State = PrintTaskProcessingState.Completed,
		Description = "completed"
	}
};

await graphClient.Print.TaskDefinitions["{taskDefinitionId}"].Tasks["{taskId}"]
	.Request()
	.UpdateAsync(printTask);

```