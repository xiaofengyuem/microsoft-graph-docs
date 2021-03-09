---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var itemEmail = new ItemEmail
{
	DisplayName = "Business Email",
	Type = EmailType.Work
};

await graphClient.Users["{userId}"].Profile.Emails["{id}"]
	.Request()
	.UpdateAsync(itemEmail);

```