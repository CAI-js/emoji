# @caijs/emoji

This library replace emojis with their equivalent text.

## Installation

In your project folder run:

```bash
$ npm install @caijs/emoji
```

## Example of use

```javascript
const removeEmojis = require('@caijs/emoji');
const actual = removeEmojis('I ❤️  ☕️! -  😯⭐️😍  ::: test : : 👍+');
console.log(actual); // I :heart:  :coffee:! -  :hushed::star::heart_eyes:  ::: test : : :thumbsup:+
```
