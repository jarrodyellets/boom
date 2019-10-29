
# Class: Boom <**Data**>

An Error object used to return an HTTP response error (4xx, 5xx)

## Type parameters

▪ **Data**

## Hierarchy

* Error

  ↳ **Boom**

## Index

### Constructors

* [constructor](boom.md#constructor)

### Properties

* [data](boom.md#optional-data)
* [isBoom](boom.md#isboom)
* [isServer](boom.md#isserver)
* [message](boom.md#message)
* [name](boom.md#name)
* [output](boom.md#output)
* [stack](boom.md#optional-stack)
* [typeof](boom.md#typeof)
* [Error](boom.md#static-error)

### Methods

* [reformat](boom.md#reformat)

## Constructors

###  constructor

\+ **new Boom**(`message?`: string | Error, `options?`: [Options](../interfaces/options.md)‹Data›): *[Boom](boom.md)*

Creates a new Boom object using the provided message

**Parameters:**

Name | Type |
------ | ------ |
`message?` | string &#124; Error |
`options?` | [Options](../interfaces/options.md)‹Data› |

**Returns:** *[Boom](boom.md)*

## Properties

### `Optional` data

• **data**? : *Data*

Custom error data with additional information specific to the error type

___

###  isBoom

• **isBoom**: *boolean*

isBoom - if true, indicates this is a Boom object instance.

___

###  isServer

• **isServer**: *boolean*

Convenience boolean indicating status code >= 500

___

###  message

• **message**: *string*

*Overrides void*

The error message

___

###  name

• **name**: *string*

*Inherited from void*

___

###  output

• **output**: *[Output](../interfaces/output.md)*

The formatted response

___

### `Optional` stack

• **stack**? : *string*

*Inherited from void*

___

###  typeof

• **typeof**: *Function*

The constructor used to create the error

___

### `Static` Error

▪ **Error**: *ErrorConstructor*

## Methods

###  reformat

▸ **reformat**(`debug?`: boolean): *string*

Specifies if an error object is a valid boom object

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`debug?` | boolean | A boolean that, when true, does not hide the original 500 error message. Defaults to false.  |

**Returns:** *string*
