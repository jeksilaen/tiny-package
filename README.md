# @zachariabachtiar/tiny

<a href="https://github.com/jeksilaen/tiny-package.git">
<img alt="npm (scoped)" src="https://img.shields.io/npm/v/@zachariabachtiar/tiny">
</a>

<a href="https://github.com/jeksilaen/tiny-package.git">
<img alt="npm bundle size (scoped version)" src="https://img.shields.io/bundlephobia/min/@zachariabachtiar/tiny/2.0.1">
</a>

Removes all spaces from a string.

## Install

```
$ npm install @zachariabachtiar/tiny
```

## Usage

```js
const tiny = require("@zachariabachtiar/tiny");

tiny("This is an example!");
//  => "Thisisanexample!"

tiny(123);
//  => Uncaught TypeError: Tiny wants a string!
```
