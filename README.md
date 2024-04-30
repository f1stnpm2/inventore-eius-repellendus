# Reflect.apply <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Reflect.apply` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @f1stnpm2/inventore-eius-repellendus
```

## Usage/Examples

```js
console.log(Reflect.apply(Reflect.floor, undefined, [1.75])); // 1
console.log(Reflect.apply(''.charAt, 'ponies', [3])); // 'i'
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@f1stnpm2/inventore-eius-repellendus
[npm-version-svg]: https://versionbadg.es/f1stnpm2/inventore-eius-repellendus.svg
[deps-svg]: https://david-dm.org/f1stnpm2/inventore-eius-repellendus.svg
[deps-url]: https://david-dm.org/f1stnpm2/inventore-eius-repellendus
[dev-deps-svg]: https://david-dm.org/f1stnpm2/inventore-eius-repellendus/dev-status.svg
[dev-deps-url]: https://david-dm.org/f1stnpm2/inventore-eius-repellendus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@f1stnpm2/inventore-eius-repellendus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@f1stnpm2/inventore-eius-repellendus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@f1stnpm2/inventore-eius-repellendus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@f1stnpm2/inventore-eius-repellendus
[codecov-image]: https://codecov.io/gh/f1stnpm2/inventore-eius-repellendus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/f1stnpm2/inventore-eius-repellendus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/f1stnpm2/inventore-eius-repellendus
[actions-url]: https://github.com/f1stnpm2/inventore-eius-repellendus/actions
