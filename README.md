# @bamblehorse/tiny

[![npm (scoped)](https://img.shields.io/github/issues/rabbygit/first_npm_package-)](https://www.npmjs.com/package/rabbyhossain)
[![npm bundle size (minified)](https://img.shields.io/github/stars/rabbygit/first_npm_package-)](https://www.npmjs.com/package/rabbyhossain)
[![npm bundle size (minified)](https://img.shields.io/github/forks/rabbygit/first_npm_package-)](https://www.npmjs.com/package/rabbyhossain)

Removes all spaces from a string.

## Install

```
$ npm install rabbyhossain
```

## Usage

```js
const removeSpace = require("rabbyhossain");

removeSpace("So much space!");
//=> "Somuchspace!"

removeSpace(1337);
//=> Uncaught TypeError: It wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1