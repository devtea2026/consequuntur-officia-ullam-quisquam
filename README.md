# @devtea2026/consequuntur-officia-ullam-quisquam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@devtea2026/consequuntur-officia-ullam-quisquam');
const Eval = require('@devtea2026/consequuntur-officia-ullam-quisquam/eval');
const Range = require('@devtea2026/consequuntur-officia-ullam-quisquam/range');
const Ref = require('@devtea2026/consequuntur-officia-ullam-quisquam/ref');
const Syntax = require('@devtea2026/consequuntur-officia-ullam-quisquam/syntax');
const Type = require('@devtea2026/consequuntur-officia-ullam-quisquam/type');
const URI = require('@devtea2026/consequuntur-officia-ullam-quisquam/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@devtea2026/consequuntur-officia-ullam-quisquam
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/consequuntur-officia-ullam-quisquam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/consequuntur-officia-ullam-quisquam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/consequuntur-officia-ullam-quisquam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/consequuntur-officia-ullam-quisquam
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2026/consequuntur-officia-ullam-quisquam
[actions-url]: https://github.com/devtea2026/consequuntur-officia-ullam-quisquam/actions
