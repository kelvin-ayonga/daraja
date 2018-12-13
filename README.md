# @kelvinlogic/daraja

[![npm (scoped)](https://img.shields.io/npm/v/@kelvinlogic/daraja.svg)](https://www.npmjs.com/package/@kelvinlogic/daraja)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@kelvinlogic/daraja.svg)](https://www.npmjs.com/package/@kelvinlogic/daraja)

Removes all spaces from a string.

## Install

```
$ npm install @kelvinlogic/daraja
```

## Usage

```js
const daraja = require("@kelvinlogic/daraja");

daraja("So much space!");
//=> "Somuchspace!"

daraja(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
