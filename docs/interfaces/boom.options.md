
# Interface: Options <**Data, Decoration**>

## Type parameters

▪ **Data**

▪ **Decoration**

## Hierarchy

* **Options**

## Index

### Properties

* [ctor](boom.options.md#optional-ctor)
* [data](boom.options.md#optional-data)
* [decorate](boom.options.md#optional-decorate)
* [message](boom.options.md#optional-message)
* [override](boom.options.md#optional-override)
* [statusCode](boom.options.md#optional-statuscode)

## Properties

### `Optional` ctor

• **ctor**? : *any*

Constructor reference used to crop the exception call stack output

___

### `Optional` data

• **data**? : *Data*

Additional error information

___

### `Optional` decorate

• **decorate**? : *Decoration*

An option with extra properties to set on the error object

___

### `Optional` message

• **message**? : *string*

Error message string

**`default`** none

___

### `Optional` override

• **override**? : *boolean*

If false, the err provided is a Boom object, and a statusCode or message are provided, the values are ignored

**`default`** true

___

### `Optional` statusCode

• **statusCode**? : *number*

The HTTP status code

**`default`** 500
