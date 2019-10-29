
# @hapi/boom

## Index

### Modules

* [unauthorized](modules/unauthorized.md)

### Classes

* [Boom](classes/boom.md)

### Interfaces

* [Decorate](interfaces/decorate.md)
* [Options](interfaces/options.md)
* [Output](interfaces/output.md)
* [Payload](interfaces/payload.md)

### Functions

* [badData](README.md#baddata)
* [badGateway](README.md#badgateway)
* [badImplementation](README.md#badimplementation)
* [badRequest](README.md#badrequest)
* [boomify](README.md#boomify)
* [clientTimeout](README.md#clienttimeout)
* [conflict](README.md#conflict)
* [entityTooLarge](README.md#entitytoolarge)
* [expectationFailed](README.md#expectationfailed)
* [failedDependency](README.md#faileddependency)
* [forbidden](README.md#forbidden)
* [gatewayTimeout](README.md#gatewaytimeout)
* [illegal](README.md#illegal)
* [internal](README.md#internal)
* [isBoom](README.md#isboom)
* [lengthRequired](README.md#lengthrequired)
* [locked](README.md#locked)
* [methodNotAllowed](README.md#methodnotallowed)
* [notAcceptable](README.md#notacceptable)
* [notFound](README.md#notfound)
* [notImplemented](README.md#notimplemented)
* [paymentRequired](README.md#paymentrequired)
* [preconditionFailed](README.md#preconditionfailed)
* [preconditionRequired](README.md#preconditionrequired)
* [proxyAuthRequired](README.md#proxyauthrequired)
* [rangeNotSatisfiable](README.md#rangenotsatisfiable)
* [resourceGone](README.md#resourcegone)
* [serverUnavailable](README.md#serverunavailable)
* [teapot](README.md#teapot)
* [tooManyRequests](README.md#toomanyrequests)
* [unsupportedMediaType](README.md#unsupportedmediatype)
* [uriTooLong](README.md#uritoolong)

## Functions

###  badData

▸ **badData**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 422 Unprocessable Entity error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 422 Unprocessable Entity error

___

###  badGateway

▸ **badGateway**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 502 Bad Gateway error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 502 Bad Gateway error

___

###  badImplementation

▸ **badImplementation**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 500 Internal Server Error error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 500 Internal Server error

___

###  badRequest

▸ **badRequest**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 400 Bad Request error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 400 bad request error

___

###  boomify

▸ **boomify**<**Data**, **Decoration**>(`err`: Error, `options?`: [Options](interfaces/options.md)‹Data› & [Decorate](interfaces/decorate.md)‹Decoration›): *[Boom](classes/boom.md)‹Data› & Decoration*

Specifies if an error object is a valid boom object

**Type parameters:**

▪ **Data**

▪ **Decoration**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`err` | Error | The error object to decorate |
`options?` | [Options](interfaces/options.md)‹Data› & [Decorate](interfaces/decorate.md)‹Decoration› | Options object  |

**Returns:** *[Boom](classes/boom.md)‹Data› & Decoration*

A decorated boom object

___

###  clientTimeout

▸ **clientTimeout**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 408 Request Time-out error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 408 Request Time-out error

___

###  conflict

▸ **conflict**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 409 Conflict error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 409 Conflict error

___

###  entityTooLarge

▸ **entityTooLarge**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 413 Request Entity Too Large error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 413 Request Entity Too Large error

___

###  expectationFailed

▸ **expectationFailed**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 417 Expectation Failed error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 417 Expectation Failed error

___

###  failedDependency

▸ **failedDependency**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 424 Failed Dependency error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 424 Failed Dependency error

___

###  forbidden

▸ **forbidden**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 403 Forbidden error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 403 Forbidden error

___

###  gatewayTimeout

▸ **gatewayTimeout**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 504 Gateway Time-out error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 504 Gateway Time-out error

___

###  illegal

▸ **illegal**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 451 Unavailable For Legal Reasons error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 451 Unavailable for Legal Reasons error

___

###  internal

▸ **internal**<**Data**>(`message?`: string, `data?`: Data, `statusCode?`: number): *[Boom](classes/boom.md)‹Data›*

Returns a internal error (defaults to 500)

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data |
`statusCode?` | number | Optional status code override. Defaults to 500.  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 500 Internal Server error

___

###  isBoom

▸ **isBoom**(`err`: Error): *boolean*

Specifies if an error object is a valid boom object

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`err` | Error | The error object  |

**Returns:** *boolean*

Returns a boolean stating if the error object is a valid boom object

___

###  lengthRequired

▸ **lengthRequired**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 411 Length Required error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 411 Length Required error

___

###  locked

▸ **locked**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 423 Locked error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 423 Locked error

___

###  methodNotAllowed

▸ **methodNotAllowed**<**Data**>(`message?`: string, `data?`: Data, `allow?`: string | string[]): *[Boom](classes/boom.md)‹Data›*

Returns a 405 Method Not Allowed error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data |
`allow?` | string &#124; string[] | Optional string or array of strings which is used to set the 'Allow' header  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 405 Method Not Allowed error

___

###  notAcceptable

▸ **notAcceptable**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 406 Not Acceptable error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 406 Not Acceptable error

___

###  notFound

▸ **notFound**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 404 Not Found error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 404 Not Found error

___

###  notImplemented

▸ **notImplemented**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 501 Not Implemented error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 501 Not Implemented error

___

###  paymentRequired

▸ **paymentRequired**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 402 Payment Required error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 402 Payment Required error

___

###  preconditionFailed

▸ **preconditionFailed**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 412 Precondition Failed error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 412 Precondition Failed error

___

###  preconditionRequired

▸ **preconditionRequired**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 428 Precondition Required error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 428 Precondition Required error

___

###  proxyAuthRequired

▸ **proxyAuthRequired**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 407 Proxy Authentication error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 407 Proxy Authentication error

___

###  rangeNotSatisfiable

▸ **rangeNotSatisfiable**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 416 Request Range Not Satisfiable error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 416 Request Range Not Satisfiable error

___

###  resourceGone

▸ **resourceGone**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 410 Gone error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 410 gone error

___

###  serverUnavailable

▸ **serverUnavailable**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 503 Service Unavailable error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 503 Service Unavailable error

___

###  teapot

▸ **teapot**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 418 I'm a Teapot error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 418 I'm a Teapot error

___

###  tooManyRequests

▸ **tooManyRequests**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 429 Too Many Requests error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 429 Too Many Requests error

___

###  unsupportedMediaType

▸ **unsupportedMediaType**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 415 Unsupported Media Type error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 415 Unsupported Media Type error

___

###  uriTooLong

▸ **uriTooLong**<**Data**>(`message?`: string, `data?`: Data): *[Boom](classes/boom.md)‹Data›*

Returns a 414 Request-URI Too Large error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string | Optional message |
`data?` | Data | Optional additional error data  |

**Returns:** *[Boom](classes/boom.md)‹Data›*

A 414 Request-URI Too Large error
