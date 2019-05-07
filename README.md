# ![LOGO](logo.png) MarketplaceOrdering.Agreements **flow**ground Connector

## Description

A generated **flow**ground connector for the MarketplaceOrdering.Agreements API (version 2015-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/marketplaceordering-Agreements/2015-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:21+03:00

## API Description

REST API for MarketplaceOrdering Agreements.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Microsoft.MarketplaceOrdering REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.

### List marketplace agreements in the subscription.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.

### Get marketplace agreement.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `publisherId` - _required_ - Publisher identifier string of image being deployed.
* `offerId` - _required_ - Offer identifier string of image being deployed.
* `planId` - _required_ - Plan identifier string of image being deployed.

### Cancel marketplace terms.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `publisherId` - _required_ - Publisher identifier string of image being deployed.
* `offerId` - _required_ - Offer identifier string of image being deployed.
* `planId` - _required_ - Plan identifier string of image being deployed.

### Sign marketplace terms.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `publisherId` - _required_ - Publisher identifier string of image being deployed.
* `offerId` - _required_ - Offer identifier string of image being deployed.
* `planId` - _required_ - Plan identifier string of image being deployed.

### Get marketplace terms.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `offerType` - _required_ - Offer Type, currently only virtualmachine type is supported.
    Possible values: virtualmachine.
* `publisherId` - _required_ - Publisher identifier string of image being deployed.
* `offerId` - _required_ - Offer identifier string of image being deployed.
* `planId` - _required_ - Plan identifier string of image being deployed.

### Save marketplace terms.

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `offerType` - _required_ - Offer Type, currently only virtualmachine type is supported.
    Possible values: virtualmachine.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `publisherId` - _required_ - Publisher identifier string of image being deployed.
* `offerId` - _required_ - Offer identifier string of image being deployed.
* `planId` - _required_ - Plan identifier string of image being deployed.

## License

**flow**ground :- Telekom iPaaS / azure-com-marketplaceordering-agreements-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
