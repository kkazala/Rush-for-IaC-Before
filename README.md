# Change Management in Infrastructure as a Code (IaC)

This repo is used in the [Change Management in Infrastructure as a Code (IaC)](https://dev.to/kkazala/version-management-in-infrastructure-as-a-code-iac-1joe) series.

It's the initial state of the project, before Rush is configured. 
it provisions the following services:

-  Workspace-based* [Application Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/app/create-workspace-resource?tabs=bicep)
-  App Service plan and Azure Function using isolated model**

> \* If you are still using classic Application Insights, you have to [migrate](https://learn.microsoft.com/en-us/azure/azure-monitor/app/convert-classic-resource) to workspace-based. 
>
> \*\* Support for the **in-process** model for .NET apps [will end in November 2026](https://azure.microsoft.com/en-us/updates/retirement-support-for-the-inprocess-model-for-net-apps-in-azure-functions-ends-10-november-2026). See [Migrate .NET apps from the in-process model to the isolated worker model](https://learn.microsoft.com/en-us/azure/azure-functions/migrate-dotnet-to-isolated-model?tabs=net8)
