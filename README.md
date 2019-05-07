# ![LOGO](logo.png) Microsoft Storage Sync **flow**ground Connector

## Description

A generated **flow**ground connector for the Microsoft Storage Sync API (version 2018-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/storagesync/2018-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:17+03:00

## API Description

Microsoft Storage Sync Service API

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Storage Sync Rest API operations.

*Tags:* `ResourceProvider` `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.

### Check the give namespace name availability.

*Tags:* `StorageSyncService`

#### Input Parameters
* `locationName` - _required_ - The desired region for the name check.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Get a StorageSyncService list by subscription.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `api-version` - _required_ - The API version to use for this operation.

### Get a StorageSyncService list by Resource group name.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.

### Delete a given StorageSyncService.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Get a given StorageSyncService.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `api-version` - _required_ - The API version to use for this operation.

### Patch a given StorageSyncService.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Create a new StorageSyncService.

*Tags:* `StorageSyncServices Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Get a given registered server list.

*Tags:* `RegisteredServer Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Delete the given registered server.

*Tags:* `RegisteredServer Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `serverId` - _required_ - GUID identifying the on-premises server.

### Get a given registered server.

*Tags:* `RegisteredServer Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `serverId` - _required_ - GUID identifying the on-premises server.

### Add a new registered server.

*Tags:* `RegisteredServer Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `serverId` - _required_ - GUID identifying the on-premises server.

### Triggers Server certificate rollover.

*Tags:* `RegisteredServer Resource` `Actions`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `serverId` - _required_ - Server Id

### Get a SyncGroup List.

*Tags:* `SyncGroup Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Delete a given SyncGroup.

*Tags:* `SyncGroup Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.

### Get a given SyncGroup.

*Tags:* `SyncGroup Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.

### Create a new SyncGroup.

*Tags:* `SyncGroup Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.

### Get a CloudEndpoint List.

*Tags:* `CloudEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.

### Delete a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Get a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Create a new CloudEndpoint.

*Tags:* `CloudEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Post Backup a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource` `Actions` `Backup Restore`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Post Restore a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource` `Actions` `Backup Restore`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Pre Backup a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource` `Actions` `Backup Restore`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Pre Restore a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource` `Actions` `Backup Restore`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Restore Heartbeat a given CloudEndpoint.

*Tags:* `CloudEndpoint Resource` `Actions` `Backup Restore`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `cloudEndpointName` - _required_ - Name of Cloud Endpoint object.

### Get a ServerEndpoint list.

*Tags:* `ServerEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.

### Delete a given ServerEndpoint.

*Tags:* `ServerEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `serverEndpointName` - _required_ - Name of Server Endpoint object.

### Get a ServerEndpoint.

*Tags:* `ServerEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `serverEndpointName` - _required_ - Name of Server Endpoint object.

### Patch a given ServerEndpoint.

*Tags:* `ServerEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `serverEndpointName` - _required_ - Name of Server Endpoint object.

### Create a new ServerEndpoint.

*Tags:* `ServerEndpoint Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `serverEndpointName` - _required_ - Name of Server Endpoint object.

### Recall a server endpoint.

*Tags:* `ServerEndpoint Resource` `Actions`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `syncGroupName` - _required_ - Name of Sync Group resource.
* `serverEndpointName` - _required_ - Name of Server Endpoint object.

### Get a Workflow List

*Tags:* `Workflow Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.

### Get Workflows resource

*Tags:* `Workflow Resource`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `workflowId` - _required_ - workflow Id

### Abort the given workflow.

*Tags:* `Workflow Resource` `Actions`

#### Input Parameters
* `subscriptionId` - _required_ - The ID of the target subscription.
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `storageSyncServiceName` - _required_ - Name of Storage Sync Service resource.
* `workflowId` - _required_ - workflow Id

## License

**flow**ground :- Telekom iPaaS / azure-com-storagesync-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
