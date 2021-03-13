---
id: common.cargo-build
title: Cargo Build
desc: ''
updated: 1615655543047
created: 1615655543047
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cargo build

> Compile a local package and all of its dependencies.
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-build.html>.

- Build the package or packages defined by the `Cargo.toml` manifest file in the local path:

`cargo build`

- Build artifacts in release mode, with optimizations:

`cargo build --release`

- Require that `Cargo.lock` is up to date:

`cargo build --locked`

- Build all packages in the workspace:

`cargo build --workspace`

- Build a specific package:

`cargo build --package {{package}}`

- Build only the specified binary:

`cargo build --bin {{name}}`

- Build only the specified test target:

`cargo build --test {{testname}}`

