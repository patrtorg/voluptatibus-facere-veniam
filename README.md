# @patrtorg/voluptatibus-facere-veniam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@patrtorg/voluptatibus-facere-veniam');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@patrtorg/voluptatibus-facere-veniam
[npm-version-svg]: https://versionbadg.es/inspect-js/@patrtorg/voluptatibus-facere-veniam.svg
[deps-svg]: https://david-dm.org/inspect-js/@patrtorg/voluptatibus-facere-veniam.svg
[deps-url]: https://david-dm.org/inspect-js/@patrtorg/voluptatibus-facere-veniam
[dev-deps-svg]: https://david-dm.org/inspect-js/@patrtorg/voluptatibus-facere-veniam/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@patrtorg/voluptatibus-facere-veniam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/voluptatibus-facere-veniam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/voluptatibus-facere-veniam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/voluptatibus-facere-veniam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/voluptatibus-facere-veniam
[codecov-image]: https://codecov.io/gh/inspect-js/@patrtorg/voluptatibus-facere-veniam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@patrtorg/voluptatibus-facere-veniam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@patrtorg/voluptatibus-facere-veniam
[actions-url]: https://github.com/patrtorg/voluptatibus-facere-veniam/actions
