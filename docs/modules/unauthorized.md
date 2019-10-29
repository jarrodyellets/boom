
# Module: unauthorized

Returns a 401 Unauthorized error

## Callable

▸ **unauthorized**<**Data**>(`message?`: string | null): *[Boom](../classes/boom.md)‹Data›*

Returns a 401 Unauthorized error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message?` | string &#124; null | Optional message |

**Returns:** *[Boom](../classes/boom.md)‹Data›*

A 401 Unauthorized error

▸ **unauthorized**<**Data**>(`message`: "" | null, `scheme`: string, `attributes?`: string | [Attributes](../interfaces/unauthorized.attributes.md)): *[Boom](../classes/boom.md)‹Data› & [MissingAuth](../interfaces/unauthorized.missingauth.md)*

Returns a 401 Unauthorized error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message` | "" &#124; null | Optional message |
`scheme` | string | the authentication scheme name |
`attributes?` | string &#124; [Attributes](../interfaces/unauthorized.attributes.md) | an object of values used to construct the 'WWW-Authenticate' header  |

**Returns:** *[Boom](../classes/boom.md)‹Data› & [MissingAuth](../interfaces/unauthorized.missingauth.md)*

A 401 Unauthorized error

▸ **unauthorized**<**Data**>(`message`: string | null, `scheme`: string, `attributes?`: string | [Attributes](../interfaces/unauthorized.attributes.md)): *[Boom](../classes/boom.md)‹Data›*

Returns a 401 Unauthorized error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message` | string &#124; null | Optional message |
`scheme` | string | - |
`attributes?` | string &#124; [Attributes](../interfaces/unauthorized.attributes.md) | - |

**Returns:** *[Boom](../classes/boom.md)‹Data›*

A 401 Unauthorized error

▸ **unauthorized**<**Data**>(`message`: string | null, `wwwAuthenticate`: string[]): *[Boom](../classes/boom.md)‹Data›*

Returns a 401 Unauthorized error

**Type parameters:**

▪ **Data**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`message` | string &#124; null | Optional message |
`wwwAuthenticate` | string[] | array of string values used to construct the wwwAuthenticate header  |

**Returns:** *[Boom](../classes/boom.md)‹Data›*

A 401 Unauthorized error

## Index

### Interfaces

* [Attributes](../interfaces/unauthorized.attributes.md)
* [MissingAuth](../interfaces/unauthorized.missingauth.md)
