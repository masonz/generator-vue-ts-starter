# generator-vue-ts-starter
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> 😘 Vue 和 TypeScript 的项目脚手架

## 集成工具

 * Vue2
 * Vuex
 * Vue-Router
 * TypeScript
 * Sass
 * Webpack3
 * Karma
 * Mocha
 * Tslint

> ⚠ 关于语法请参考 [vue-class-component](https://github.com/vuejs/vue-class-component) 和 [vue-property-decorator](https://github.com/kaorun343/vue-property-decorator)

## 安装

使用 `npm` 安装 [Yeoman](http://yeoman.io) 和 [generator-vue-ts-starter](https://www.npmjs.com/package/generator-vue-ts-starter) .

```bash
npm install -g yo
npm install -g generator-vue-ts-starter
```

生成项目结构:

```bash
yo vue-ts-starter
```

生成`组件`或者`页面`目录：

```bash
yo vue-ts-starter:component
yo vue-ts-starter:page
```

如果构建过程中遇到`main.scss`报错:
```
ERROR in ./node_modules/css-loader!./node_modules/sass-loader/lib/loader.js!./src/sass/main.scss
Module build failed: Error: ENOENT: no such file or directory, scandir '/Users/masonz/Project/my-project/node_modules/node-sass/vendor'
```
请尝试 `npm rebuild node-sass` 后再次构建

## License

MIT © masonz

[npm-image]: https://badge.fury.io/js/generator-vue-ts-starter.svg
[npm-url]: https://npmjs.org/package/generator-vue-ts-starter
[travis-image]: https://travis-ci.org/masonz/generator-vue-ts-starter.svg?branch=master
[travis-url]: https://travis-ci.org/masonz/generator-vue-ts-starter
[daviddm-image]: https://david-dm.org/masonz/generator-vue-ts-starter.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/masonz/generator-vue-ts-starter
[coveralls-image]: https://coveralls.io/repos/masonz/generator-vue-ts-starter/badge.svg
[coveralls-url]: https://coveralls.io/r/masonz/generator-vue-ts-starter
