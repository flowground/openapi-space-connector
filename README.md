# ![LOGO](logo.png) OpenAPI space **flow**ground Connector

## Description

A generated **flow**ground connector for the OpenAPI space API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/openapi.space/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:24+03:00

## API Description

This is the API for OpenAPI space.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Retrieves a list of currently defined APIs in API meta list format.

*Tags:* `APIs`

#### Input Parameters
* `query` - _optional_ - free text query to match
* `limit` - _optional_ - the maximum number of APIs to return
* `offset` - _optional_ - the offset where to start from when fetching a limited number of APIs
* `sort` - _optional_ - sort criteria or result set
* NAME -
* UPATED
* CREATED
* OWNER

    Possible values: NAME, UPDATED, CREATED, OWNER.
* `order` - _optional_ - sort order
    Possible values: ASC, DESC.

### Retrieves an API meta listing of all APIs defined for this owner

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `sort` - _optional_ - sort criteria or result set
* NAME -
* UPATED
* CREATED
* OWNER

    Possible values: NAME, UPDATED, CREATED, OWNER.
* `order` - _optional_ - sort order
    Possible values: ASC, DESC.

### Deletes the specified API

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier

### Retrieves an API meta listing for all API versions for this owner and API

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier

### Saves the provided Swagger definition

> Saves the provided Swagger definition; the owner must match the token owner. The version will be extracted from the Swagger definitions itself.

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier
* `private` - _optional_ - Defines whether the API has to be private
* `force` - _optional_ - force update

### Deletes a particular version of the specified API

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier
* `version` - _required_ - version identifier

### Publish a particular version of the specified API

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier
* `version` - _required_ - version identifier

### Retrieves the Swagger definition for the specified API and version in JSON format

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier
* `version` - _required_ - version identifier

### Retrieves the Swagger definition for the specified API and version in YAML format

*Tags:* `APIs`

#### Input Parameters
* `owner` - _required_ - API owner identifier
* `api` - _required_ - API identifier
* `version` - _required_ - version identifier

### Log in to OpenAPI space

*Tags:* `Auth`

### Log in to OpenAPI space using an APInf account

*Tags:* `Auth`

### Log in to OpenAPI space using an APInf authentication token

*Tags:* `Auth`

### Log out from OpenAPI space

*Tags:* `Auth`

### Check whether or not you are authenticated

*Tags:* `Auth`

### Register to OpenAPI space

*Tags:* `Auth`

## License

**flow**ground :- Telekom iPaaS / openapi-space-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
