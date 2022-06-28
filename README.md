# @bamblehorse/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@suxuan/tiny.svg)](https://www.npmjs.com/package/@suxuan/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@suxuan/tiny.svg)](https://www.npmjs.com/package/@suxuan/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @suxuan/tiny
```

## Usage

```js
const tiny = require("@suxuan/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
