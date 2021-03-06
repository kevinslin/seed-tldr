---
id: common.cargo-clippy
title: Cargo Clippy
desc: ''
updated: 1623965306176
created: 1623965306176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cargo clippy

> A collection of lints to catch common mistakes and improve your Rust code.
> More information: <https://github.com/rust-lang/rust-clippy>.

- Run checks over the code in the current directory:

`cargo clippy`

- Require that `Cargo.lock` is up to date:

`cargo clippy --locked`

- Run checks on all packages in the workspace:

`cargo clippy --workspace`

- Run checks for a package:

`cargo clippy --package {{package}}`

- Treat warnings as errors:

`RUSTFLAGS="-Dwarnings" cargo clippy -- -D warnings`

- Run checks and ignore warnings:

`cargo clippy -- -A warnings`

- Apply Clippy suggestion automatically (experimental and only supported on the nightly channel):

`cargo clippy --fix -Z unstable-options`

