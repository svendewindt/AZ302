# AZ-302

[https://www.microsoft.com/en-us/learning/exam-az-302.aspx](https://www.microsoft.com/en-us/learning/exam-az-302.aspx)

## Multichannel learning

[Azure updates & announcements](https://azure.microsoft.com/en-us/updates/)

- [Microsoft learning portal](https://microsoft.com/learn)
  - search for `solution architecture content`
- [Microsoft handson labs](https://microsoft.com/handsonlabs)
  - search for `Azure`
- [Microsoft documentation for Azure](https://docs.microsoft.com/en-us/azure)
- [Azure Citadel](https://azurecitadel.com/)
- [Microsoft Azure Youtube Channel](https://www.youtube.com/user/windowsazure)
- [Azure Github repository](https://github.com/Azure/azure-powershell)
- [Azure REST API browser](https://docs.microsoft.com/en-us/rest/api/?view=Azure)
- [Architect great Azure solutions](https://docs.microsoft.com/en-us/learn/paths/architect-great-solutions-in-azure/)

### Determine Workload Requirements (15-20%)

Determine feasibility and refine requirments

- POC
- Pilot project (reduce risks)
- Agile - refine user stories
- Handle change during execution

Optimize Consumption Stategy

- Save money
- Right size to the correct plan size
- Turn off resources when not used
- Auto-Scaling
- Azure Advisor
- Cost management and optimization tools
- Reports, alerts
- Rearchitecting to use cheaper methods Paas, Serverless

[Goto page](./1.%20Determine%20Workload%20Requirements.md)

### Design for Identity and Security (5-10%)

- Authorization Approach
- RBAC
- Azure AD Conditional Access
- Azure AD Privileged Identity Management
- Azure Key Vault for secrets
  - API keys
  - Devs don't see keys
  - Certificates

[Goto page](./2.%20Design%20for%20Identity%20and%20Security.md)

### Design a Business Continuity Strategy (15-20%)

Design a Site Recovery Strategy

- BC is about from a terrible disaster
- Data center is not accessible
- Should never happen
- Azure Site Recovery (ASR)! You will be down for some time.
  - Azure to Azure, On-Prem to Azure
- Have everything ready in case of disaster

Design for High Availability

- Protect against single point of failure
- Everything redundant
- Autoscaling
- No human intervention

[Goto page](./3.%20Design%20a%20Business%20Continuity%20Strategy.md)

### Implement Workloads and Security (5-10%)

Configure serverless computing

- Logic apps
- Functions
- Event Grid
- Service Bus

[Goto page](./4.%20Implement%20Workloads%20and%20Security.md)

### Implement Authentication and Secure Data (5-10%)

Implement secure data solutions

- Azure Key Vault
- Encrypt data at rest
- Azure Confidential Compute - encrypt data while in use

[Goto page](./5.%20Implement%20Authentication%20and%20Secure%20Data.md)

### Develop for the Cloud (25-30%)

Configure a message-based integration architecture

- Emails
- By message or by event
  - Message has content -> reader wil act
  - Event does not contain data, only the link
- Queue Storage
- Service Bus
- Event Grid makes it easy to connect events to serverless applications

Develop for autoscaling

- Scale by
  - cpu
  - weekdays / weekends
  - holidays
  - custom metric (Application Insights)

[Goto page](./6.%20Develop%20for%20the%20Cloud.md)