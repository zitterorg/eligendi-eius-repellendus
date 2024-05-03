# @zitterorg/eligendi-eius-repellendus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @zitterorg/eligendi-eius-repellendus
```

## Usage/Examples

```js
var regexTester = require('@zitterorg/eligendi-eius-repellendus');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/eligendi-eius-repellendus
[npm-version-svg]: https://versionbadg.es/ljharb/@zitterorg/eligendi-eius-repellendus.svg
[deps-svg]: https://david-dm.org/ljharb/@zitterorg/eligendi-eius-repellendus.svg
[deps-url]: https://david-dm.org/ljharb/@zitterorg/eligendi-eius-repellendus
[dev-deps-svg]: https://david-dm.org/ljharb/@zitterorg/eligendi-eius-repellendus/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@zitterorg/eligendi-eius-repellendus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/eligendi-eius-repellendus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/eligendi-eius-repellendus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/eligendi-eius-repellendus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/eligendi-eius-repellendus
[codecov-image]: https://codecov.io/gh/ljharb/@zitterorg/eligendi-eius-repellendus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@zitterorg/eligendi-eius-repellendus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@zitterorg/eligendi-eius-repellendus
[actions-url]: https://github.com/zitterorg/eligendi-eius-repellendus/actions
