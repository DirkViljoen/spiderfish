# spiderfish
The package that does that random stuff you always wanted

![](https://img.shields.io/github/issues/DirkViljoen/spiderfish.svg)
[![npm (scoped)](https://img.shields.io/npm/v/@dirkviljoen/spiderfish.svg)](https://img.shields.io/github/DirkViljoen/spiderfish.svg)

## Install

```
$ npm install @dirkviljoen/spiderfish
```

## Usage

```js
const spiderfish = require("@dirkviljoen/spiderfish");

spiderfish("So much space!");
//=> "Somuchspace!"

spiderfish(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```