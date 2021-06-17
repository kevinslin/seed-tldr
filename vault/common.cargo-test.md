---
id: common.cargo-test
title: Cargo Test
desc: ''
updated: 1623965016116
created: 1623965016116
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cargo test

> Execute the unit and integration tests of a Rust package.
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-test.html>.

- Only run tests containing a specific string in their names:

`cargo test {{testname}}`

- Set the number of simultaneous running test cases:

`cargo test -- --test-threads={{count}}`

- Require that `Cargo.lock` is up to date:

`cargo test --locked`

- Test artifacts in release mode, with optimizations:

`cargo test --release`

- Test all packages in the workspace:

`cargo test --workspace`

- Run tests for a package:

`cargo test --package {{package}}`

