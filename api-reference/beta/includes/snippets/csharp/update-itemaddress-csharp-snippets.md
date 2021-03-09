---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var itemAddress = new ItemAddress
{
	AllowedAudiences = AllowedAudiences.Me,
	DisplayName = "Secret Hideout"
};

await graphClient.Users["{userId}"].Profile.Addresses["{id}"]
	.Request()
	.UpdateAsync(itemAddress);

```