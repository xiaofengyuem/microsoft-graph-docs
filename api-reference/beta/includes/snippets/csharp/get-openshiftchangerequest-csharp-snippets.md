---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var openShiftChangeRequest = await graphClient.Teams["{id}"].Schedule.OpenShiftChangeRequests["SREQ_0b87dd20-d5ed-4764-9c3e-cfc8516def09"]
	.Request()
	.GetAsync();

```