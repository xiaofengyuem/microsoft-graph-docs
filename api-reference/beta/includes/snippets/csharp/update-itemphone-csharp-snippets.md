---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var itemPhone = new ItemPhone
{
	Type = PhoneType.Other
};

await graphClient.Users["{userId}"].Profile.Phones["{id}"]
	.Request()
	.UpdateAsync(itemPhone);

```