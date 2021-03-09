---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var appRoleAssignments = await graphClient.Users["cdb555e3-b33e-4fd5-a427-17fadacbdfa7"].AppRoleAssignments
	.Request()
	.Filter("resourceId eq 8e881353-1735-45af-af21-ee1344582a4d")
	.GetAsync();

```