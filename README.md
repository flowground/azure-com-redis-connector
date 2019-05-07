# ![LOGO](logo.png) RedisManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RedisManagementClient API (version 2018-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/redis/2018-03-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:42+03:00

## API Description

REST API for Azure Redis Cache Service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available REST API operations of the Microsoft.Cache provider.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Checks that the redis cache name is valid and is not already in use.

*Tags:* `Redis`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all Redis caches in the specified subscription.

*Tags:* `Redis`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all Redis caches in a resource group.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all firewall rules in the specified redis cache.

*Tags:* `Redis` `FirewallRules`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `cacheName` - _required_ - The name of the Redis cache.

### Deletes a single firewall rule in a specified redis cache.

*Tags:* `Redis` `FirewallRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `cacheName` - _required_ - The name of the Redis cache.
* `ruleName` - _required_ - The name of the firewall rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a single firewall rule in a specified redis cache.

*Tags:* `Redis` `FirewallRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `cacheName` - _required_ - The name of the Redis cache.
* `ruleName` - _required_ - The name of the firewall rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a redis cache firewall rule

*Tags:* `Redis` `FirewallRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `cacheName` - _required_ - The name of the Redis cache.
* `ruleName` - _required_ - The name of the firewall rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all patch schedules in the specified redis cache (there is only one).

*Tags:* `Redis` `PatchSchedules`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `cacheName` - _required_ - The name of the Redis cache.

### Deletes a Redis cache.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a Redis cache (resource description).

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update an existing Redis cache.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Export data from the redis cache to blobs in a container.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Reboot specified Redis node(s). This operation requires write permission to the cache resource. There can be potential data loss.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Import data into Redis cache.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the list of linked servers associated with this redis cache (requires Premium SKU).

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the linked server from a redis cache (requires Premium SKU).

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the redis cache.
* `linkedServerName` - _required_ - The name of the linked server that is being added to the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the detailed information about a linked server of a redis cache (requires Premium SKU).

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the redis cache.
* `linkedServerName` - _required_ - The name of the linked server.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Adds a linked server to the Redis cache (requires Premium SKU).

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `linkedServerName` - _required_ - The name of the linked server that is being added to the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Retrieve a Redis cache's access keys. This operation requires write permission to the cache resource.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets any upgrade notifications for a Redis cache.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `history` - _required_ - how many minutes in past to look for upgrade notifications

### Deletes the patching schedule of a redis cache (requires Premium SKU).

*Tags:* `Redis` `PatchSchedules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the redis cache.
* `default` - _required_ - Default string modeled as parameter for auto generation to work correctly.
    Possible values: default.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the patching schedule of a redis cache (requires Premium SKU).

*Tags:* `Redis` `PatchSchedules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the redis cache.
* `default` - _required_ - Default string modeled as parameter for auto generation to work correctly.
    Possible values: default.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or replace the patching schedule for Redis cache (requires Premium SKU).

*Tags:* `Redis` `PatchSchedules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `default` - _required_ - Default string modeled as parameter for auto generation to work correctly.
    Possible values: default.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerate Redis cache's access keys. This operation requires write permission to the cache resource.

*Tags:* `Redis`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `name` - _required_ - The name of the Redis cache.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-redis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
