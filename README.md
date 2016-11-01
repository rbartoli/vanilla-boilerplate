# Vanilla boilerplate (ES2015)
A boilerplate to start a client-side project using Vanilla JavaScript (ES2015).

## Features
- [ES2015](https://babeljs.io/docs/learn-es2015)
- [SASS](http://sass-lang.com/) support using [node-sass](https://github.com/sass/node-sass)

## Tools
- [Webpack](https://github.com/webpack/webpack)
    - [webpack-dev-server](https://github.com/webpack/webpack-dev-server) with HMR support
    - [webpack-notifier](https://github.com/Turbo87/webpack-notifier)
- [Babel 6](https://github.com/babel/babel) with presets for:
    - ES2015 using [babel-preset-es2015](https://github.com/babel/babel/tree/master/packages/babel-preset-es2015)
- [ESLint](https://github.com/eslint/eslint) configured to:
    - use Babel 6 as parser using [babel-eslint](https://github.com/babel/babel-eslint)
    - lint page on save using [eslint-loader](https://github.com/MoOx/eslint-loader)

## Getting started
```bash
$ git clone https://github.com/rbartoli/vanilla-boilerplate.git
$ npm i
$ npm start
```
