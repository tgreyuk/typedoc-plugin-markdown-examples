[single-page-modules-example](README.md) / utilities

# utilities

This module contains generic utility functions.

## Functions

### formatCurrency()

> **formatCurrency**(`amount`, `currencyCode`): `string`

Function to format a number as currency.

#### Parameters

• **amount**: `number`

The amount to be formatted.

• **currencyCode**: `string`

The currency code (e.g., USD, EUR).

#### Returns

`string`

The formatted currency string.

#### Source

[utilities.ts:14](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L14)

***

### generateUniqueId()

> **generateUniqueId**(): `string`

Function to generate a unique identifier.

#### Returns

`string`

A unique identifier.

#### Source

[utilities.ts:36](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L36)

***

### isValidEmail()

> **isValidEmail**(`email`): `boolean`

Function to check if a value is a valid email address.

#### Parameters

• **email**: `string`

The email address to be validated.

#### Returns

`boolean`

True if the email address is valid, false otherwise.

#### Source

[utilities.ts:60](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L60)

***

### shuffleArray()

> **shuffleArray**\<`T`\>(`array`): `T`[]

Function to shuffle an array.

#### Type parameters

• **T**

#### Parameters

• **array**: `T`[]

The array to be shuffled.

#### Returns

`T`[]

The shuffled array.

#### Source

[utilities.ts:70](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L70)

***

### toTitleCase()

> **toTitleCase**(`input`): `string`

Function to convert a string to title case.

#### Parameters

• **input**: `string`

The input string.

#### Returns

`string`

The input string in title case.

#### Source

[utilities.ts:26](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L26)

***

### truncateString()

> **truncateString**(`input`, `maxLength`): `string`

Function to truncate a string to a specified length.

#### Parameters

• **input**: `string`

The input string.

• **maxLength**: `number`

The maximum length of the truncated string.

#### Returns

`string`

The truncated string.

#### Source

[utilities.ts:48](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/d1574a7/examples/01-typedoc-plugin-markdown/src/utilities.ts#L48)
