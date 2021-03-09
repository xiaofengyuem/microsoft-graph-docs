---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var outputName = "2020-12-06 Contoso investigation export";

var description = "Export for the Contoso investigation";

var exportOptions = Microsoft.Graph.Ediscovery.ExportOptions.OriginalFiles | Microsoft.Graph.Ediscovery.ExportOptions.FileInfo | Microsoft.Graph.Ediscovery.ExportOptions.Tags;

var exportStructure = Microsoft.Graph.Ediscovery.ExportFileStructure.Directory;

await graphClient.Compliance.Ediscovery.Cases["99e865fc-e29f-479a-ba83-9e58eb017103"].ReviewSets["e44ac2cb-f8b4-4fd8-aa1c-1391b46ba9cc"]
	.Export(exportStructure,outputName,description,null,null,exportOptions)
	.Request()
	.PostAsync();

```