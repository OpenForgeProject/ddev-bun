<div align="center">
    <a href="https://ddev.com/">
        <img src="https://raw.githubusercontent.com/ddev/ddev/master/images/ddev-logo.svg" alt="DDEV logo" height="80">
    </a>
    <a href="https://bun.sh">
        <img src="https://user-images.githubusercontent.com/709451/182802334-d9c42afe-f35d-4a7b-86ea-9985f73f20c3.png"
            alt="Bun Logo"
            height="80"
        >
    </a>
    <h1 align="center">ddev-bun</h1>
</div>

[![tests](https://github.com/OpenForgeProject/ddev-bun/actions/workflows/tests.yml/badge.svg)](https://github.com/OpenForgeProject/ddev-bun/actions/workflows/tests.yml)
![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

## What is Bun?

> Bun is an all-in-one JavaScript runtime & toolkit designed for speed,
> complete with a bundler, test runner, and Node.js-compatible package manager.

For more information,
see [What is Bun?](https://github.com/oven-sh/bun#what-is-bun)
or visit <https://bun.sh/>.

YouTube: [Bun 1.0 is here](https://www.youtube.com/watch?v=BsnCpESUEqM)

## Installation

```shell
ddev add-on get OpenForgeProject/ddev-bun
ddev restart
```

> [!NOTE]
> For DDEV versions prior to v1.23.5, use `ddev get` instead of `ddev add-on get`.

## Usage

```shell
ddev bun
```

Please refer to the documentation at <https://bun.sh/docs>.

Quick links:

- [RUNTIME](https://bun.sh/docs/cli/run)
- [PACKAGE MANAGER](https://bun.sh/docs/cli/install)
- [BUNDLER](https://bun.sh/docs/bundler)
- [TEST RUNNER](https://bun.sh/docs/cli/test)
- [PACKAGE RUNNER](https://bun.sh/docs/cli/bunx)
