ES5-Basic
=========

This library provides some basic shim methods to make older browsers more
ECMAScript 5 compatible. All the methods in this module should match the
behavior of the specification. For newer browsers, the built-in methods will
be used.


Contents
--------

* Function.prototype.bind
* Array.isArray
* Array.prototype.forEach
* Array.prototype.map
* Array.prototype.filter
* Array.prototype.every
* Array.prototype.some
* Array.prototype.reduce
* Array.prototype.reduceRight
* Array.prototype.indexOf
* Array.prototype.lastIndexOf
* Object.keys
* Date.now
* Date.prototype.toISOString
* Date.prototype.toJSON
* String.prototype.trim

Acknowledgements
----------------

This module is modeled after the great
[es5-shim module](https://github.com/kriskowal/es5-shim). If you're looking
for a shim module that has greater completeness at the cost of larger code
size and some methods that can't be implemented to match the spec, then
es5-shim is what you should get.