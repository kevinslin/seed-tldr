---
id: common.rustup
title: Rustup
desc: ''
updated: 1615655543083
created: 1615655543083
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rustup

> Rust toolchain installer.
> Install, manage, and update Rust toolchains.
> More information: <https://github.com/rust-lang/rustup.rs>.

- Install the nightly toolchain for your system:

`rustup install nightly`

- Switch the default toolchain to nightly so that the `cargo` and `rustc` commands will use it:

`rustup default nightly`

- Use the nightly toolchain when inside the current project, but leave global settings unchanged:

`rustup override set nightly`

- Update all toolchains:

`rustup update`

- List installed toolchains:

`rustup show`

- Run cargo build with a certain toolchain:

`rustup run {{toolchain_name}} cargo build`

