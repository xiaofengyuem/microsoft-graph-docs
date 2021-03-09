---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var itemPublication = new ItemPublication
{
	Publisher = "International Association of Branding Management Publishing",
	ThumbnailUrl = "https://iabm.io/sdhdfhsdhshsd.jpg"
};

await graphClient.Users["{userId}"].Profile.Publications["{id}"]
	.Request()
	.UpdateAsync(itemPublication);

```