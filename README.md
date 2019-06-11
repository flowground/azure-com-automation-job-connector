# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2017-05-15-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-job/2017-05-15-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:25+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of jobs.

*Tags:* `Job`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `$filter` - _optional_ - The filter to apply on the operation.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Retrieve the job identified by job name.

*Tags:* `Job`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Create a job of the runbook.

*Tags:* `Job`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Retrieve the job output identified by job name.

*Tags:* `Job`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The name of the job to be created.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Resume the job identified by jobName.

*Tags:* `Job`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Retrieve the runbook content of the job identified by job name.

*Tags:* `Job`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Stop the job identified by jobName.

*Tags:* `Job`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Retrieve a list of jobs streams identified by job name.

*Tags:* `JobStream`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `$filter` - _optional_ - The filter to apply on the operation.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Retrieve the job stream identified by job stream id.

*Tags:* `JobStream`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `jobStreamId` - _required_ - The job stream id.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

### Suspend the job identified by job name.

*Tags:* `Job`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `jobName` - _required_ - The job name.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-job-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
