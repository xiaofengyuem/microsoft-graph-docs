---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var personAward = new PersonAward
{
	IssuingAuthority = "International Association of Branding Management",
	ThumbnailUrl = "https://iabm.io/sdhdfhsdhshsd.jpg"
};

await graphClient.Users["{userId}"].Profile.Awards["{personAwardId}"]
	.Request()
	.UpdateAsync(personAward);

```