# AzureQuotas
Azure Quotas Quotas into Azure Monitor Logs (Using PowerShell)

Credit to Tom Hollander for the original solution: https://blogs.msdn.microsoft.com/tomholl/2017/06/11/get-alerts-as-you-approach-your-azure-resource-quotas/

Updates the original Powershell script to add the following:
- Updated from AzureRM to Az (Make sure to import Az.Account, Az.Compute and Az.Storage modules into your Automation Account).
- Added per Subscription capabilities (via Parameter)
