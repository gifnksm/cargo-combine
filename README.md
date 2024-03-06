<!-- cargo-sync-rdme title [[ -->
# cargo-combine
<!-- cargo-sync-rdme ]] -->
<!-- cargo-sync-rdme badge [[ -->
[![Maintenance: actively-developed](https://img.shields.io/badge/maintenance-actively--developed-brightgreen.svg?style=flat-square)](https://doc.rust-lang.org/cargo/reference/manifest.html#the-badges-section)
[![License: MIT OR Apache-2.0](https://img.shields.io/crates/l/cargo-combine.svg?style=flat-square)](#license)
[![crates.io](https://img.shields.io/crates/v/cargo-combine.svg?logo=rust&style=flat-square)](https://crates.io/crates/cargo-combine)
[![docs.rs](https://img.shields.io/docsrs/cargo-combine.svg?logo=docs.rs&style=flat-square)](https://docs.rs/cargo-combine)
[![Rust: ^1.74.0](https://img.shields.io/badge/rust-^1.74.0-93450a.svg?logo=rust&style=flat-square)](https://doc.rust-lang.org/cargo/reference/manifest.html#the-rust-version-field)
[![GitHub Actions: CI](https://img.shields.io/github/actions/workflow/status/gifnksm/cargo-combine/ci.yml.svg?label=CI&logo=github&style=flat-square)](https://github.com/gifnksm/cargo-combine/actions/workflows/ci.yml)
[![Codecov](https://img.shields.io/codecov/c/github/gifnksm/cargo-combine.svg?label=codecov&logo=codecov&style=flat-square)](https://codecov.io/gh/gifnksm/cargo-combine)
<!-- cargo-sync-rdme ]] -->

A Cargo subcommand that outputs a matrix of build parameters based on workspace paths, packages names, feature names to enable, and toolchain versions.

## Installation

There are multiple ways to install cargo-combine.
Choose any one of the methods below that best suits your needs.

### Pre-built binaries

Executable binaries are available for download on the [GitHub Release page].

[GitHub Release page]: https://github.com/gifnksm/cargo-combine/releases/

### Build from source using Rust

To build cargo-combine executable from the source, you must have the Rust toolchain installed.
To install the rust toolchain, follow [this guide](https://www.rust-lang.org/tools/install).

Once you have installed Rust, the following command can be used to build and install cargo-combine:

```console
# Install released version
$ cargo install cargo-combine

# Install latest version
$ cargo install --git https://github.com/gifnksm/cargo-combine.git cargo-combine
```

## Minimum supported Rust version (MSRV)

The minimum supported Rust version is **Rust 1.74.0**.
At least the last 3 versions of stable Rust are supported at any given time.

While a crate is a pre-release status (0.x.x) it may have its MSRV bumped in a patch release.
Once a crate has reached 1.x, any MSRV bump will be accompanied by a new minor version.

## License

This project is licensed under either of

* Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).
