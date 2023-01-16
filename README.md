<div class="text-xs-center" align="center" style="margin: 20px">
  <img src="https://raw.githubusercontent.com/fxwz100/rollup-plugin-vue2/master/docs/.vuepress/public/logo.png">
</div>

## Introduction

As vue-loader is for webpack, so is this for rollup. As we know, webpack concats stuff and makes it runnable in the browser. It's difficult to share .vue components. **Now roll your [Vue](http://vuejs.org/) components.**

With rollup you can break your application into reusable modules.

## Usage

```js
import commonjs from '@rollup/plugin-commonjs' 
import VuePlugin from 'rollup-plugin-vue2'

export default {
  entry: 'main.js',
  plugins: [
    commonjs(),
    VuePlugin(/* VuePluginOptions */)
  ]
}
```

See [available options](https://rollup-plugin-vue.vuejs.org/options.html) for `VuePluginOptions` (please review the options for Vue 2 if possible).

## Security

If you discover any security related issues, please email yfwz100@yeah.net instead of using the issue tracker.

## Credits

* [Rahul Kadyan](https://github.com/znck)
* [Thomas Ghysels](https://github.com/thgh)
* [Eduardo San Martin Morote](https://github.com/posva)
* [All Contributors][link-contributors]

## License

The MIT License (MIT).

[link-contributors]: https://github.com/fwz100/rollup-plugin-vue2/graphs/contributors
