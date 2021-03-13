---
id: common.cargo-build
title: Cargo Build
desc: ''
updated: 1615663978702
created: 1615663978702
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

