<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# ndarray Native Add-ons

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> C APIs for creating N-API ndarray native add-ons.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

This package exposes an absolute file path for the directory containing header files for various C APIs. The various C APIs facilitate the creation of N-API ndarray native add-ons.

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/ndarray-base-napi
```

</section>

<section class="usage">

## Usage

```javascript
var headerDir = require( '@stdlib/ndarray-base-napi' );
```

#### headerDir

Absolute file path for the directory containing header files for C APIs.

```javascript
var dir = headerDir;
// returns <string>
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

```javascript
var headerDir = require( '@stdlib/ndarray-base-napi' );

console.log( headerDir );
// => <string>
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->

* * *

<section class="c">

## C APIs

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

This package exposes various C APIs to facilitate the creation of N-API ndarray native add-ons. The included C APIs are the APIs implemented in the following packages:

<!-- NOTE: please keep in alphabetical order -->

-   [`@stdlib/ndarray/base/napi/unary`][@stdlib/ndarray/base/napi/unary]: N-API interfaces and macros for registering one or more [`@stdlib/ndarray/base/unary`][@stdlib/ndarray/base/unary] interfaces with support for multiple dispatch.
-   [`@stdlib/ndarray/base/unary`][@stdlib/ndarray/base/unary]: ndarray loops for operating on a single input ndarray and one or more output ndarrays.
-   [`@stdlib/ndarray/dtypes`][@stdlib/ndarray/dtypes]: supported ndarray data types.

For API documentation, consult the individual packages.

</section>

<!-- /.intro -->

<!-- C usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/ndarray-base-napi
```

</section>

<section class="usage">

### Usage

```c
#include "stdlib/ndarray/base/napi.h"
```

</section>

<!-- /.usage -->

<!-- C API usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- C API usage examples. -->

<section class="examples">

### Examples

```c
#include "stdlib/ndarray/base/napi.h"

// TODO
```

</section>

<!-- /.examples -->

</section>

<!-- /.c -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/ndarray-base-napi.svg
[npm-url]: https://npmjs.org/package/@stdlib/ndarray-base-napi

[test-image]: https://github.com/stdlib-js/ndarray-base-napi/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/ndarray-base-napi/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/ndarray-base-napi/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/ndarray-base-napi?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/ndarray-base-napi.svg
[dependencies-url]: https://david-dm.org/stdlib-js/ndarray-base-napi/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/ndarray-base-napi/main/LICENSE

[@stdlib/ndarray/base/napi/unary]: https://github.com/stdlib-js/ndarray-base-napi-unary

[@stdlib/ndarray/base/unary]: https://github.com/stdlib-js/ndarray-base-unary

[@stdlib/ndarray/dtypes]: https://github.com/stdlib-js/ndarray-dtypes

</section>

<!-- /.links -->
