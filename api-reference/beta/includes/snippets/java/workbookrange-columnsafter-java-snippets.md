---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

graphClient.drive().root().workbook().worksheets("{id}")
	.range()
	.columnsAfter(WorkbookRangeColumnsAfterParameterSet
		.newBuilder()
		.withCount(null)
		.build())
	.buildRequest()
	.post();

```