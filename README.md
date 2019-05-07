# ![LOGO](logo.png) RunCommandsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RunCommandsClient API (version 2018-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/compute-runCommands/2018-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:49+03:00

## API Description

The Run Commands Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all available run commands for a subscription in a location.

*Tags:* `VirtualMachineRunCommands`

#### Input Parameters
* `location` - _required_ - The location upon which run commands is queried.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets specific run command for a subscription in a location.

*Tags:* `VirtualMachineRunCommands`

#### Input Parameters
* `location` - _required_ - The location upon which run commands is queried.
* `commandId` - _required_ - The command id.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Run command on a virtual machine in a VM scale set.

*Tags:* `VirtualMachineScaleSetVMs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `vmScaleSetName` - _required_ - The name of the VM scale set.
* `instanceId` - _required_ - The instance ID of the virtual machine.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Run command on the VM.

*Tags:* `VirtualMachines`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `vmName` - _required_ - The name of the virtual machine.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-compute-run-commands-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
