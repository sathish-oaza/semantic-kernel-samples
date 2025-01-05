# Chat Plugin

This console application demonstrates the use of the OpenAI Chat Completion API with function calling and Semantic Kernel.

Since the OpenAI Chat Completion API supports function calling, the example shows how to combine it with Semantic Kernel plugins and functions.

## Configuring Secrets

The example requires credentials to access OpenAI or Azure OpenAI.

```
cd dotnet/samples/Demos/OpenAIRuntime

dotnet user-secrets init

dotnet user-secrets set "OpenAI:ApiKey" "..."

dotnet user-secrets set "AzureOpenAI:DeploymentName" "..."
dotnet user-secrets set "AzureOpenAI:Endpoint" "https://... .openai.azure.com/"
dotnet user-secrets set "AzureOpenAI:ApiKey" "..."
```
