[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache 2.0 License][license-shield]][license-url]

<br />
<div align="center">
  <h1 align="center">Paco Examples</h1>

  <p align="center">
    Example programs demonstrating the Paco programming language
    <br />
    <a href="https://github.com/pacolang/paco"><strong>Explore the paco compiler »</strong></a>
    <br />
    <br />
    <a href="https://github.com/pacolang/examples/issues">Report an issue</a>
    ·
    <a href="https://github.com/pacolang/examples/pulls">Contribute an example</a>
  </p>
</div>

**Read this in:** **English** · [Português](README.pt-BR.md) · [Español](README.es.md)

## Table of Contents

<ol>
  <li><a href="#about-the-project">About The Project</a></li>
  <li><a href="#getting-started">Getting Started</a>
    <ul>
      <li><a href="#prerequisites">Prerequisites</a></li>
    </ul>
  </li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#contact">Contact</a></li>
</ol>

## About The Project

This repository holds example Paco programs. Each one is a small,
self-contained demonstration of a specific language feature or standard
library capability — concurrency, pattern matching, automatic
differentiation, and so on — rather than a full application.

Examples used to live inside `examples/` in the [`pacolang/paco`][paco-url]
compiler repository. They were moved here so the compiler repository can
stay focused on the compiler, runtime and standard library, while this one
can grow independently as new examples are added.

Current examples:

- [`http-server/main.paco`](http-server/main.paco) — a minimal HTTP/1.1
  server that spawns one task per connection, demonstrating Paco's
  concurrency model.

## Getting Started

### Prerequisites

You need a working `paco` binary on your `PATH`. See
[`pacolang/paco`][paco-url] for how to build or install it — the README
there covers the toolchain requirements and build steps.

## Usage

Clone this repository and run any example with `paco run`, pointing at its
`.paco` entry point:

```sh
git clone https://github.com/pacolang/examples.git
cd examples
paco run examples/http-server/main.paco
```

(Adjust the path to the entry point for whichever example you want to run —
single-file examples run directly, and examples with their own subdirectory
run via their `main.paco`.)

## Contributing

New examples are welcome. If you have a small, focused program that shows
off a Paco language feature or standard library API well, open a pull
request:

1. Fork the repository.
2. Create a branch for your example (`git checkout -b add-example-name`).
3. Add your example in its own file or subdirectory, with a short comment
   at the top explaining what it demonstrates.
4. Commit your changes and open a pull request.

## License

Distributed under the Apache License 2.0. See [`LICENSE`](LICENSE) for
more information.

## Contact

Project Link: [https://github.com/pacolang/paco](https://github.com/pacolang/paco)

[paco-url]: https://github.com/pacolang/paco
[contributors-shield]: https://img.shields.io/github/contributors/pacolang/examples.svg?style=for-the-badge
[contributors-url]: https://github.com/pacolang/examples/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pacolang/examples.svg?style=for-the-badge
[forks-url]: https://github.com/pacolang/examples/network/members
[stars-shield]: https://img.shields.io/github/stars/pacolang/examples.svg?style=for-the-badge
[stars-url]: https://github.com/pacolang/examples/stargazers
[issues-shield]: https://img.shields.io/github/issues/pacolang/examples.svg?style=for-the-badge
[issues-url]: https://github.com/pacolang/examples/issues
[license-shield]: https://img.shields.io/github/license/pacolang/examples.svg?style=for-the-badge
[license-url]: https://github.com/pacolang/examples/blob/main/LICENSE
