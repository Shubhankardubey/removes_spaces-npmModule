# @@comrade.js/removes_spaces

[![npm (scoped)](https://img.shields.io/npm/v/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@comrade.js/removes_spaces)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@comrade.js/removes_spaces.svg)](https://www.npmjs.com/package/@comrade.js/removes_spaces)

Removes all spaces from a string.

## Install

```
$ npm install @@comrade.js/removes_spaces
```

## Usage

```js
const tiny = require("@comrade.js/removes_spaces");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
