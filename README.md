# xScheme

[![Join the chat at https://gitter.im/exercism/xscheme](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/exercism/xscheme?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Exercism exercises in the Scheme Programming Language

## Setup

You'll need a vaguely [R6RS](http://www.r6rs.org/)-compliant Scheme implementation. As of this writing, the exercises are being developed in [Guile Scheme](http://www.gnu.org/software/guile/), but the tests are using [SFRI-64](http://srfi.schemers.org/srfi-64/srfi-64.html), and so should (hopefully) be rather implementation-agnostic.

## Working on Problems

Each problem should have a test suite and an example solution, as well as a stub file for the solution declaring the module and exports. The example solution should be named `example.scm`.

## Dependencies

Try to avoid external dependencies. It will often be necessary to use various
modules included in the Guile distribution, such as the ice-9 and srfi
collections. When using these modules in exercises/examples, please use the
`#:autoload` directive in `(define-module)` rather than `(use-modules ...)` for
the sake of consistency, and to give a clue which functions are being relied
upon.

## Contributing Guide

Please see the [contributing guide](https://github.com/exercism/x-api/blob/master/CONTRIBUTING.md#the-exercise-data)

## License

The MIT License (MIT)

Copyright (c) 2014 Katrina Owen, _@kytrinyx.com
