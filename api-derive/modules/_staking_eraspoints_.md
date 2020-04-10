[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["staking/erasPoints"](_staking_eraspoints_.md)

# Module: "staking/erasPoints"

## Index

### Functions

* [erasPoints](_staking_eraspoints_.md#eraspoints)
* [erasPointsOver](_staking_eraspoints_.md#eraspointsover)

## Functions

###  erasPoints

▸ **erasPoints**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasPoints.ts:40](https://github.com/polkadot-js/api/blob/5ab24390c5/packages/api-derive/src/staking/erasPoints.ts#L40)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`withActive?`: undefined | false | true): *Observable‹DeriveEraPoints[]›*

**Parameters:**

Name | Type |
------ | ------ |
`withActive?` | undefined &#124; false &#124; true |

___

###  erasPointsOver

▸ **erasPointsOver**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasPoints.ts:24](https://github.com/polkadot-js/api/blob/5ab24390c5/packages/api-derive/src/staking/erasPoints.ts#L24)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`eras`: EraIndex[]): *Observable‹DeriveEraPoints[]›*

**Parameters:**

Name | Type |
------ | ------ |
`eras` | EraIndex[] |
