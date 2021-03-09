---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var appRoleAssignments = await graphClient.ServicePrincipals["8e881353-1735-45af-af21-ee1344582a4d"].AppRoleAssignments
	.Request()
	.GetAsync();

```