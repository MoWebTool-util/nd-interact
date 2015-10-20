# nd-interact

[![spm version](http://spm.crossjs.com/badge/nd-interact)](http://spm.crossjs.com/package/nd-interact)

> interaction plugin from grid and tree

## 安装

```bash
$ spm install nd-interact --save
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
