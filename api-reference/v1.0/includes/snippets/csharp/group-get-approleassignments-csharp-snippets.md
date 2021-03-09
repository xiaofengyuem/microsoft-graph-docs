---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var appRoleAssignments = await graphClient.Groups["7679d9a4-2323-44cd-b5c2-673ec88d8b12"].AppRoleAssignments
	.Request()
	.GetAsync();

```