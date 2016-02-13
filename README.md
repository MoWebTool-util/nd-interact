# nd-interact

[![Travis](https://img.shields.io/travis/ndfront/nd-interact.svg?style=flat-square)](https://github.com/ndfront/nd-interact)
[![Coveralls](https://img.shields.io/coveralls/ndfront/nd-interact.svg?style=flat-square)](https://github.com/ndfront/nd-interact)
[![NPM version](https://img.shields.io/npm/v/nd-interact.svg?style=flat-square)](https://npmjs.org/package/nd-interact)

> interaction plugin from grid and tree

## 安装

```bash
$ npm install nd-interact --save
```

## 使用

```js
var Widget = require('nd-widget');
// use interact on Class
var SomeWidget = Widget.extend({
  Plugins: [{
    name: 'interact',
    priority: 0,
    starter: require('nd-interact')
  }]
})
// use interact on instance
new Widget({
  plugins: [{
    name: 'interact',
    priority: 0,
    starter: require('nd-interact')
  }]
})
```
