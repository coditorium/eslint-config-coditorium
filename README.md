# Coditorium eslint configuration

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
- `react` - Use it for [react](https://facebook.github.io/react/) projects.
- `koa` - Use it for [koa](http://koajs.com/) based projects.
