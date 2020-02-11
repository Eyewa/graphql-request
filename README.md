# @eyewa/graphql-request

##### Forked from https://github.com/prisma-labs/graphql-request

Please follow `https://github.com/prisma-labs/graphql-request` documentation for the general integration guides. We only document the extended functionalities.

## Install
___

Install using npm
```js
npm install @eyewa/graphql-request
```
Install using yarn
```js
yarn add @eyewa/graphql-request
```


## Usage

```js
import { GraphQLClient } from 'graphql-request'
// ... or create a GraphQL client instance to send requests
const client = new GraphQLClient(endpoint, { headers: {} })
client.query(query, variables).then(data => console.log(data))
```
