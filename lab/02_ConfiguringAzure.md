# Configuring the Agent

## Configure Application Insights
Follow the steps outlined [here to setup Azure Application Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/app/create-workspace-resource?tabs=portal).

Follow the steps outlined [here to setup the Data Export from Microsoft Dataverse to Azure Application Insights](https://learn.microsoft.com/en-us/power-platform/admin/set-up-export-application-insights?tabs=new).

## Configuring the Query connector
The query connector uses the Azure Monitor Logs connector. You'll need to connect using an account that has access to the Azure resource. To configure, you need to set the following:
- Subscription
- Resource Group
- Application Insights name

![](/img/ConfigureQueryConnector.png)

NOTE: You can also use the Log Analytics workspace. The benefits including searching across multiple Application Insights resources that use Log Analytics as the log data store.