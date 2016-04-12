# start-with <sup>[![Version Badge](http://versionbadg.es/bubkoo/start-with.svg)](https://npmjs.org/package/start-with)</sup>


> Determines whether a string begins with the characters of another string.

> ES2015 [String#startsWith()](http://www.ecma-international.org/ecma-262/6.0/#sec-string.prototype.startswith) ponyfill.

> Ponyfill: A polyfill that doesn't overwrite the native method.



[![MIT License](https://img.shields.io/badge/license-MIT_License-green.svg?style=flat-square)](https://github.com/bubkoo/start-with/blob/master/LICENSE)

[![build:?](https://img.shields.io/travis/bubkoo/start-with/master.svg?style=flat-square)](https://travis-ci.org/bubkoo/start-with)
[![coverage:?](https://img.shields.io/coveralls/bubkoo/start-with/master.svg?style=flat-square)](https://coveralls.io/github/bubkoo/start-with)


## Install

```
$ npm install --save start-with 
```

## Usage

> For more use-cases see the [tests](https://github.com/bubkoo/start-with/blob/master/test/spec/index.js)

```js
var startWith = require('start-with');

startWith('abcde', 'a');  // => true
startWith('abcde', 'ab'); // => true
startWith('abcde', 'bc'); // => false
startWith('abcde', '');   // => true
startWith('abcde');       // => false
startWith('abcde', null); // => false

```

## Related

- [end-with](https://github.com/bubkoo/end-with) - Determines whether a string ends with the characters of another string.
- [pad-start](https://github.com/bubkoo/pad-start) - ES spec-compliant String.prototype.padStart shim.
- [pad-end](https://github.com/bubkoo/pad-end) - ES spec-compliant String.prototype.padEnd shim.


## Contributing
 
Pull requests and stars are highly welcome. 

For bugs and feature requests, please [create an issue](https://github.com/bubkoo/start-with/issues).
