# Dataverse Monitoring Agent Dependencies
This document lists the dependencies for the Dataverse Monitoring Agent.

# Dependencies
- Microsoft Dataverse
- Azure Application Insights service
- Azure Kusto MCP Server
- Microsoft Word MCP
- Azure Log Analytics connector
- Claude Sonnet

### Microsoft Dataverse
Used to connect to the flow session information stored within Dataverse. 
[Learn More](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/data-platform-mcp)

### Azure Application Insights service
This is used to connect to telemetry exported from Dataverse to Azure Application Insights. Can include Dataverse, Canvas App and Power Automate telemetry.
[Learn More](https://learn.microsoft.com/en-us/power-platform/admin/set-up-export-application-insights?tabs=new)

### Kusto Query MCP Server
This is used to query Azure Application Insights. It can be used independently from the Azure Application Insights service.
[Learn More](https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-data-explorer)

### Microsoft Word MCP
This is used to generate reports on the fly. It is used to create word documents analyzing trends and providing helpful recommendations.
[Learn More](https://learn.microsoft.com/en-us/microsoft-agent-365/mcp-server-reference/word)

### Azure Log Analytics connector
TBD

### Claude Sonnet
The LLM used by the agent. Sonnet's reasoning assist with slot filling and creating reports.
Security information regarding Anthropic can be found [here](https://copilot.github.trust.page/faq?s=qoerjag9v36a9muz82voo)