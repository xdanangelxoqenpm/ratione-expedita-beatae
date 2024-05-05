# @xdanangelxoqenpm/ratione-expedita-beatae <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@xdanangelxoqenpm/ratione-expedita-beatae');
const Eval = require('@xdanangelxoqenpm/ratione-expedita-beatae/eval');
const Range = require('@xdanangelxoqenpm/ratione-expedita-beatae/range');
const Ref = require('@xdanangelxoqenpm/ratione-expedita-beatae/ref');
const Syntax = require('@xdanangelxoqenpm/ratione-expedita-beatae/syntax');
const Type = require('@xdanangelxoqenpm/ratione-expedita-beatae/type');
const URI = require('@xdanangelxoqenpm/ratione-expedita-beatae/uri');

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

[package-url]: https://npmjs.org/package/@xdanangelxoqenpm/ratione-expedita-beatae
[npm-version-svg]: https://versionbadg.es/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae.svg
[deps-svg]: https://david-dm.org/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae.svg
[deps-url]: https://david-dm.org/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae
[dev-deps-svg]: https://david-dm.org/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@xdanangelxoqenpm/ratione-expedita-beatae.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@xdanangelxoqenpm/ratione-expedita-beatae.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@xdanangelxoqenpm/ratione-expedita-beatae.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@xdanangelxoqenpm/ratione-expedita-beatae
[codecov-image]: https://codecov.io/gh/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@xdanangelxoqenpm/ratione-expedita-beatae
[actions-url]: https://github.com/xdanangelxoqenpm/ratione-expedita-beatae/actions
