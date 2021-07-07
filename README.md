# @chandrakanthd/tiny

![npm (scoped)](https://img.shields.io/npm/v/@chandrakanthd/tiny)

It's very tiny!

## Install

```
$ npm install @chandrakanthd/tiny
```

## Usage

```js
const tiny = require("@chandrakanthd/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```