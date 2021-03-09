---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var hubSiteUrls = new List<String>()
{
	"https://graph.microsoft.com/beta/sites/id"
};

var propagateToExistingLists = false;

await graphClient.Sites["id"].ContentTypes["id"]
	.AssociateWithHubSites(hubSiteUrls,propagateToExistingLists)
	.Request()
	.PostAsync();

```