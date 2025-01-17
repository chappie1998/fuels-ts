---
layout: default
title: StringCoder
parent: "@fuel-ts/abi-coder"
nav_order: 1

---

# Class: StringCoder<TLength\>

[@fuel-ts/abi-coder](../index.md).StringCoder

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | extends `number` = `number` |

## Hierarchy

- [`Coder`](Coder.md)<`string`, `string`\>

  ↳ **`StringCoder`**

## Constructors

### constructor

• **new StringCoder**<`TLength`\>(`length`)

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | extends `number` = `number` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `TLength` |

#### Overrides

[Coder](Coder.md).[constructor](Coder.md#constructor)

## Properties

### #paddingLength

• `Private` **#paddingLength**: `number`

#### Defined in

[packages/abi-coder/src/coders/string.ts:8](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/string.ts#L8)

___

### encodedLength

• `Readonly` **encodedLength**: `number`

#### Inherited from

[Coder](Coder.md).[encodedLength](Coder.md#encodedlength)

#### Defined in

[packages/abi-coder/src/coders/abstract-coder.ts:36](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/abstract-coder.ts#L36)

___

### length

• **length**: `TLength`

#### Defined in

[packages/abi-coder/src/coders/string.ts:7](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/string.ts#L7)

___

### name

• `Readonly` **name**: `string`

#### Inherited from

[Coder](Coder.md).[name](Coder.md#name)

#### Defined in

[packages/abi-coder/src/coders/abstract-coder.ts:34](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/abstract-coder.ts#L34)

___

### offset

• `Optional` **offset**: `number`

#### Inherited from

[Coder](Coder.md).[offset](Coder.md#offset)

#### Defined in

[packages/abi-coder/src/coders/abstract-coder.ts:37](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/abstract-coder.ts#L37)

___

### type

• `Readonly` **type**: `string`

#### Inherited from

[Coder](Coder.md).[type](Coder.md#type)

#### Defined in

[packages/abi-coder/src/coders/abstract-coder.ts:35](https://github.com/FuelLabs/fuels-ts/blob/master/packages/abi-coder/src/coders/abstract-coder.ts#L35)

## Methods

### decode

▸ **decode**(`data`, `offset`): [`string`, `number`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` |
| `offset` | `number` |

#### Returns

[`string`, `number`]

#### Overrides

[Coder](Coder.md).[decode](Coder.md#decode)

___

### encode

▸ **encode**(`value`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`Uint8Array`

#### Overrides

[Coder](Coder.md).[encode](Coder.md#encode)

___

### setOffset

▸ **setOffset**(`offset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `offset` | `number` |

#### Returns

`void`

#### Inherited from

[Coder](Coder.md).[setOffset](Coder.md#setoffset)

___

### throwError

▸ **throwError**(`message`, `value`): `never`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `value` | `unknown` |

#### Returns

`never`

#### Inherited from

[Coder](Coder.md).[throwError](Coder.md#throwerror)
