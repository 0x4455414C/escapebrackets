## Escape Square Brackets
Escapes square brackets in a string, useful for queries and other such things.
## Install
```bash
$ npm install escapebrackets
```
## Usage
	escapebrackets(string)
**In JS**
```js
var escapebrackets = require('escapebrackets');
input = "[1 mark]";
input = escapebrackets(input);

```
**Output**
```
\[1 mark\]
```
