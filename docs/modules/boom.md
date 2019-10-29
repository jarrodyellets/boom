
# Module: Boom <**Data**>

## Type parameters

▪ **Data**

## Index

### Modules

* [unauthorized](boom.unauthorized.md)

### Interfaces

* [Options](../interfaces/boom.options.md)
* [Output](../interfaces/boom.output.md)
* [Payload](../interfaces/boom.payload.md)

### Properties

* [Error](boom.md#error)
* [data](boom.md#optional-data)
* [isBoom](boom.md#isboom)
* [isServer](boom.md#isserver)
* [message](boom.md#message)
* [name](boom.md#name)
* [output](boom.md#output)
* [stack](boom.md#optional-stack)
* [typeof](boom.md#typeof)

### Methods

* [reformat](boom.md#reformat)

## Properties

###  Error

• **Error**: *ErrorConstructor*

___

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

Convenience bool indicating status code >= 500

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

• **output**: *[Output](../interfaces/boom.output.md)*

The formatted response

___

### `Optional` stack

• **stack**? : *string*

*Inherited from void*

___

###  typeof

• **typeof**: *any*

The constructor used to create the error

## Methods

###  reformat

▸ **reformat**(`debug?`: boolean): *string*

Specifies if an error object is a valid boom object

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`debug?` | boolean | A boolean that, when true, does not hide the original 500 error message. Defaults to false.  |

**Returns:** *string*
