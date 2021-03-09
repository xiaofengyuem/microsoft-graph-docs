---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var personCertification = new PersonCertification
{
	IssuingAuthority = "International Academy of Marketing Excellence",
	IssuingCompany = "International Academy of Marketing Excellence"
};

await graphClient.Users["{userId}"].Profile.Certifications["{id}"]
	.Request()
	.UpdateAsync(personCertification);

```