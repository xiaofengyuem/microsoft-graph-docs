---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var authenticationMethodConfiguration = new EmailAuthenticationMethodConfiguration
{
	AllowExternalIdToUseEmailOtp = ExternalEmailOtpState.Default
};

await graphClient.Policies.AuthenticationMethodsPolicy.AuthenticationMethodConfigurations["email"]
	.Request()
	.UpdateAsync(authenticationMethodConfiguration);

```