[@zeldafan0225/ai_horde](../README.md) / [Exports](../modules.md) / AIHordeInitOptions

# Interface: AIHordeInitOptions

## Table of contents

### Properties

- [api\_route](AIHordeInitOptions.md#api_route)
- [cache](AIHordeInitOptions.md#cache)
- [cache\_interval](AIHordeInitOptions.md#cache_interval)
- [client\_agent](AIHordeInitOptions.md#client_agent)
- [default\_token](AIHordeInitOptions.md#default_token)
- [ratings\_api\_route](AIHordeInitOptions.md#ratings_api_route)

## Properties

### api\_route

• `Optional` **api\_route**: `string`

The base api domain + route to use for requests

#### Defined in

[index.ts:1287](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1287)

___

### cache

• `Optional` **cache**: [`AIHordeCacheConfiguration`](AIHordeCacheConfiguration.md)

The configuration for caching results

#### Defined in

[index.ts:1278](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1278)

___

### cache\_interval

• `Optional` **cache\_interval**: `number`

The interval to check expired data in the cache

**`Default`**

```ts
1000
```

#### Defined in

[index.ts:1283](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1283)

___

### client\_agent

• `Optional` **client\_agent**: `string`

The client agent to pass in the requests.

#### Defined in

[index.ts:1291](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1291)

___

### default\_token

• `Optional` **default\_token**: `string`

The default token to use for requests

#### Defined in

[index.ts:1285](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1285)

___

### ratings\_api\_route

• `Optional` **ratings\_api\_route**: `string`

The ratings api domain + route to use for requests

#### Defined in

[index.ts:1289](https://github.com/ZeldaFan0225/ai_horde/blob/1d5fbc0/index.ts#L1289)
