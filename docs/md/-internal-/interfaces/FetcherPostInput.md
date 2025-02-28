[**@paraswap/sdk**](../../README.md) • **Docs**

***

[@paraswap/sdk](../../globals.md) / [\<internal\>](../README.md) / FetcherPostInput

# Interface: FetcherPostInput\<URL\>

## Extends

- [`FetcherInputBase`](FetcherInputBase.md)\<`URL`\>

## Type Parameters

• **URL** *extends* `string` = `string`

## Properties

### data

> **data**: [`Record`](../type-aliases/Record.md)\<`string`, `any`\>

#### Defined in

[src/types.ts:54](https://github.com/paraswap/paraswap-sdk/blob/master/src/types.ts#L54)

***

### headers?

> `optional` **headers**: [`Record`](../type-aliases/Record.md)\<`string`, `string`\>

#### Inherited from

[`FetcherInputBase`](FetcherInputBase.md).[`headers`](FetcherInputBase.md#headers)

#### Defined in

[src/types.ts:44](https://github.com/paraswap/paraswap-sdk/blob/master/src/types.ts#L44)

***

### method

> **method**: `"POST"`

#### Defined in

[src/types.ts:53](https://github.com/paraswap/paraswap-sdk/blob/master/src/types.ts#L53)

***

### signal?

> `optional` **signal**: `AbortSignal`

#### Inherited from

[`FetcherInputBase`](FetcherInputBase.md).[`signal`](FetcherInputBase.md#signal)

#### Defined in

[src/types.ts:45](https://github.com/paraswap/paraswap-sdk/blob/master/src/types.ts#L45)

***

### url

> **url**: `URL`

#### Inherited from

[`FetcherInputBase`](FetcherInputBase.md).[`url`](FetcherInputBase.md#url)

#### Defined in

[src/types.ts:43](https://github.com/paraswap/paraswap-sdk/blob/master/src/types.ts#L43)
