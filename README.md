# @caijs/emoji

[![Build Status](https://travis-ci.com/CAI-js/emoji.svg?branch=master)](https://travis-ci.com/CAI-js/emoji)
[![Coverage Status](https://coveralls.io/repos/github/CAI-js/emoji/badge.svg?branch=master)](https://coveralls.io/github/CAI-js/emoji?branch=master)
[![NPM version](https://img.shields.io/npm/v/@caijs/emoji.svg?style=flat)](https://www.npmjs.com/package/@caijs/emoji)
[![NPM downloads](https://img.shields.io/npm/dm/@caijs/emoji.svg?style=flat)](https://www.npmjs.com/package/@caijs/emoji)

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
