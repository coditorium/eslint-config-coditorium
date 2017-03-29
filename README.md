# Coditorium eslint configuration

[![Travis Build](https://img.shields.io/travis/coditorium/eslint-config-coditorium.svg?style=flat-square)](https://travis-ci.org/coditorium/eslint-config-coditorium)
[![Codecov Coverage](https://img.shields.io/codecov/c/github/coditorium/eslint-config-coditorium.svg?style=flat-square)](https://codecov.io/github/coditorium/eslint-config-coditorium)
[![NPM Version](https://img.shields.io/npm/v/eslint-config-coditorium.svg?style=flat-square)](http://npm.im/eslint-config-coditorium)
[![NPM Downloads](https://img.shields.io/npm/dm/eslint-config-coditorium.svg?style=flat-square)](http://npm-stat.com/charts.html?package=eslint-config-coditorium&from=2015-08-01)
[![MIT License](https://img.shields.io/npm/l/eslint-config-coditorium.svg?style=flat-square)](http://opensource.org/licenses/MIT)

It an [eslint](http://eslint.org/) configuration used in [Coditorium](https://github.com/coditorium).
It is an extension of well known [eslint-airbnb-config](https://github.com/airbnb/javascript).

This configuration does not use `peerDependencies`. it means that when you install `eslint-config-coditorium` it will be installed with all its eslint-plugins.

For more details on eslint shareable configuration see the [documentation](http://eslint.org/docs/developer-guide/shareable-configs).

## Sample usage

Create `.eslintrc` in project root directory and add:

```yaml
extends: coditorium
```

For [koa](http://koajs.com/) based project use specific configuration:

```yaml
extends: 'coditorium/koa'
```

## Different configurations

- `index` - Use it for any [es6](http://es6-features.org/) projects.
- `node` - Use it for a [node.js](https://nodejs.org/) projects.
- `react` - Use it for [react](https://facebook.github.io/react/) projects.
- `koa` - Use it for [koa](http://koajs.com/) based projects.
