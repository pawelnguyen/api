[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["staking/stakerPoints"](_staking_stakerpoints_.md)

# Module: "staking/stakerPoints"

## Index

### Functions

* [stakerPoints](_staking_stakerpoints_.md#stakerpoints)
* [stakerPointsOver](_staking_stakerpoints_.md#stakerpointsover)

## Functions

###  stakerPoints

▸ **stakerPoints**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/stakerPoints.ts:30](https://github.com/polkadot-js/api/blob/8aa1bd5bd0/packages/api-derive/src/staking/stakerPoints.ts#L30)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`accountId`: Uint8Array | string, `withActive?`: undefined | false | true): *Observable‹DeriveStakerPoints[]›*

**Parameters:**

Name | Type |
------ | ------ |
`accountId` | Uint8Array &#124; string |
`withActive?` | undefined &#124; false &#124; true |

___

###  stakerPointsOver

▸ **stakerPointsOver**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/stakerPoints.ts:14](https://github.com/polkadot-js/api/blob/8aa1bd5bd0/packages/api-derive/src/staking/stakerPoints.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`accountId`: Uint8Array | string, `eras`: EraIndex[]): *Observable‹DeriveStakerPoints[]›*

**Parameters:**

Name | Type |
------ | ------ |
`accountId` | Uint8Array &#124; string |
`eras` | EraIndex[] |
