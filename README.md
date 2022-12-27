# demo-api
Temporary repo to work through DefaultAzureCredential issues when running in container.

Have reference to Azure Key Vault in main.cs.
Am able to obtain default credential running native code, but can't get when running in container.

Error message: 

EnvironmentCredential authentication unavailable. Environment variables are not fully configured. See the troubleshooting guide for more information. https://aka.ms/azsdk/net/identity/environmentcredential/troubleshoot

Azure.Identity.CredentialUnavailableException: EnvironmentCredential authentication unavailable. Environment variables are not fully configured. 

Understand why I'm unable to obtain, but trying to find the workaround.

