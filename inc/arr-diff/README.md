# arr-diff [![NPM version](https://badge.fury.io/js/arr-diff.svg)](http://badge.fury.io/js/arr-diff)  [![Build Status](https://travis-ci.org/jonschlinkert/arr-diff.svg)](https://travis-ci.org/jonschlinkert/arr-diff)

> Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons.

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i arr-diff --save
```

Install with [bower](http://bower.io/)

```sh
$ bower install arr-diff --save
```

## API

### [diff](index.js#L33)

Return the difference between the first array and additional arrays.

**Params**

* `a` **{Array}**
* `b` **{Array}**
* `returns` **{Array}**

**Example**

```js
var diff = require('arr-diff');

var a = ['a', 'b', 'c', 'd'];
var b = ['b', 'c'];

console.log(diff(a, b))
//=> ['a', 'd']
```

## Related projects

* [arr-flatten](https://www.npmjs.com/package/arr-flatten): Recursively flatten an array or arrays. This is the fastest implementation of array flatten. | [homepage](https://github.com/jonschlinkert/arr-flatten)
* [array-filter](https://www.npmjs.com/package/array-filter): Array#filter for older browsers. | [homepage](https://github.com/juliangruber/array-filter)
* [array-intersection](https://www.npmjs.com/package/array-intersection): Return an array with the unique values present in _all_ given arrays using strict equality… [more](https://www.npmjs.com/package/array-intersection) | [homepage](https://github.com/jonschlinkert/array-intersection)

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/arr-diff/issues/new).

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on August 23, 2015._
