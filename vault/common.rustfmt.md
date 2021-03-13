---
id: common.rustfmt
title: Rustfmt
desc: ''
updated: 1615655543083
created: 1615655543083
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rustfmt

> Tool for formatting Rust source code.
> More information: <https://github.com/rust-lang/rustfmt>.

- Format a file, overwriting the original file in-place:

`rustfmt {{source.rs}}`

- Check a file for formatting and display any changes on the console:

`rustfmt --check {{source.rs}}`

- Backup any modified files before formatting (the original file is renamed with a `.bk` extension):

`rustfmt --backup {{source.rs}}`

