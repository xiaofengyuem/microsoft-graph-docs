---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

graphClient.me().drive().root().workbook().worksheets("{id}")
	.range()
	.columnsBefore(WorkbookRangeColumnsBeforeParameterSet
		.newBuilder()
		.withCount(null)
		.build())
	.buildRequest()
	.post();

```