---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var tagsToAdd = new List<Microsoft.Graph.Ediscovery.Tag>()
{
	new Microsoft.Graph.Ediscovery.Tag
	{
		Id = "b4798d14-748d-468e-a1ec-96a2b1d49677"
	}
};

await graphClient.Compliance.Ediscovery.Cases["47746044-fd0b-4a30-acfc-5272b691ba5b"].ReviewSets["6c95c2a6-31fa-45a8-93ef-dd4531974783"].Queries["b4798d14-748d-468e-a1ec-96a2b1d49677"]
	.ApplyTags(tagsToAdd,null)
	.Request()
	.PostAsync();

```