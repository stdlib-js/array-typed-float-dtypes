<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

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

# Data Types

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> List of typed array floating-point data types.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

```javascript
import dtypes from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-typed-float-dtypes@esm/index.mjs';
```

#### dtypes()

Returns a list of typed array floating-point data types.

```javascript
var out = dtypes();
// e.g., returns [ 'float32', 'float64', 'complex64', 'complex128' ]
```

The output `array` contains the following data types:

-   `float32`: single-precision floating-point numbers.
-   `float64`: double-precision floating-point numbers.
-   `complex64`: single-precision complex floating-point numbers.
-   `complex128`: double-precision complex floating-point numbers.

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import indexOf from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-index-of@esm/index.mjs';
import dtypes from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-typed-float-dtypes@esm/index.mjs';

var DTYPES = dtypes();

function isdtype( str ) {
    if ( indexOf( DTYPES, str ) === -1 ) {
        return false;
    }
    return true;
}

var bool = isdtype( 'float64' );
// returns true

bool = isdtype( 'complex128' );
// returns true

bool = isdtype( 'float32' );
// returns true

bool = isdtype( 'beep' );
// returns false

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/array-typed-float-dtypes.svg
[npm-url]: https://npmjs.org/package/@stdlib/array-typed-float-dtypes

[test-image]: https://github.com/stdlib-js/array-typed-float-dtypes/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/array-typed-float-dtypes/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/array-typed-float-dtypes/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/array-typed-float-dtypes?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/array-typed-float-dtypes.svg
[dependencies-url]: https://david-dm.org/stdlib-js/array-typed-float-dtypes/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/array-typed-float-dtypes/tree/deno
[umd-url]: https://github.com/stdlib-js/array-typed-float-dtypes/tree/umd
[esm-url]: https://github.com/stdlib-js/array-typed-float-dtypes/tree/esm
[branches-url]: https://github.com/stdlib-js/array-typed-float-dtypes/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/array-typed-float-dtypes/main/LICENSE

</section>

<!-- /.links -->
