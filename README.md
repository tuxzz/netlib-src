# netlib-src [![Package][package-img]][package-url] [![Documentation][documentation-img]][documentation-url] [![Build][build-img]][build-url]

The package provides an implementation of [BLAS] and [LAPACK] via [Netlib]. The
usage of the package is explained [here][usage].

The following Cargo features are supported:

* `cblas` to build CBLAS (enabled by default),
* `lapacke` to build LAPACKE (enabled by default),
* `static` to link to Netlib statically, and
* `system` to skip building the bundled Netlib.

## Contribution

Your contribution is highly appreciated. Do not hesitate to open an issue or a
pull request. Note that any contribution submitted for inclusion in the project
will be licensed according to the terms given in [LICENSE.md](LICENSE.md).

[blas]: https://en.wikipedia.org/wiki/BLAS
[lapack]: https://en.wikipedia.org/wiki/LAPACK
[netlib]: http://www.netlib.org/
[usage]: https://blas-lapack-rs.github.io/usage

[build-img]: https://travis-ci.org/cmr/netlib-src.svg?branch=master
[build-url]: https://travis-ci.org/cmr/netlib-src
[documentation-img]: https://docs.rs/netlib-src/badge.svg
[documentation-url]: https://docs.rs/netlib-src
[package-img]: https://img.shields.io/crates/v/netlib-src.svg
[package-url]: https://crates.io/crates/netlib-src
