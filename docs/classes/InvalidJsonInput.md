[redis-om](../README.md) / InvalidJsonInput

# Class: InvalidJsonInput

## Hierarchy

- [`InvalidInput`](InvalidInput.md)

  ↳ **`InvalidJsonInput`**

## Table of contents

### Constructors

- [constructor](InvalidJsonInput.md#constructor)

### Properties

- [cause](InvalidJsonInput.md#cause)
- [message](InvalidJsonInput.md#message)
- [name](InvalidJsonInput.md#name)
- [stack](InvalidJsonInput.md#stack)
- [prepareStackTrace](InvalidJsonInput.md#preparestacktrace)
- [stackTraceLimit](InvalidJsonInput.md#stacktracelimit)

### Accessors

- [fieldName](InvalidJsonInput.md#fieldname)
- [fieldType](InvalidJsonInput.md#fieldtype)
- [jsonPath](InvalidJsonInput.md#jsonpath)

### Methods

- [captureStackTrace](InvalidJsonInput.md#capturestacktrace)

## Constructors

### constructor

• **new InvalidJsonInput**(`field`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | [`Field`](Field.md) |

#### Overrides

[InvalidInput](InvalidInput.md).[constructor](InvalidInput.md#constructor)

#### Defined in

[lib/error/invalid-input.ts:25](https://github.com/redis/redis-om-node/blob/4f5798b/lib/error/invalid-input.ts#L25)

## Properties

### cause

• `Optional` **cause**: `unknown`

#### Inherited from

[InvalidInput](InvalidInput.md).[cause](InvalidInput.md#cause)

#### Defined in

node_modules/typescript/lib/lib.es2022.error.d.ts:26

___

### message

• **message**: `string`

#### Inherited from

[InvalidInput](InvalidInput.md).[message](InvalidInput.md#message)

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1054

___

### name

• **name**: `string`

#### Inherited from

[InvalidInput](InvalidInput.md).[name](InvalidInput.md#name)

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1053

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

[InvalidInput](InvalidInput.md).[stack](InvalidInput.md#stack)

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1055

___

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`See`**

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

##### Returns

`any`

#### Inherited from

[InvalidInput](InvalidInput.md).[prepareStackTrace](InvalidInput.md#preparestacktrace)

#### Defined in

node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

[InvalidInput](InvalidInput.md).[stackTraceLimit](InvalidInput.md#stacktracelimit)

#### Defined in

node_modules/@types/node/globals.d.ts:13

## Accessors

### fieldName

• `get` **fieldName**(): `string`

#### Returns

`string`

#### Defined in

[lib/error/invalid-input.ts:31](https://github.com/redis/redis-om-node/blob/4f5798b/lib/error/invalid-input.ts#L31)

___

### fieldType

• `get` **fieldType**(): [`FieldType`](../README.md#fieldtype)

#### Returns

[`FieldType`](../README.md#fieldtype)

#### Defined in

[lib/error/invalid-input.ts:32](https://github.com/redis/redis-om-node/blob/4f5798b/lib/error/invalid-input.ts#L32)

___

### jsonPath

• `get` **jsonPath**(): `string`

#### Returns

`string`

#### Defined in

[lib/error/invalid-input.ts:33](https://github.com/redis/redis-om-node/blob/4f5798b/lib/error/invalid-input.ts#L33)

## Methods

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

[InvalidInput](InvalidInput.md).[captureStackTrace](InvalidInput.md#capturestacktrace)

#### Defined in

node_modules/@types/node/globals.d.ts:4
