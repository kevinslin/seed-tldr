---
id: common.rustup
title: Rustup
desc: ''
updated: 1642441815066
created: 1642441815066
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

- Open the local rust documentation in the default web browser:

`rustup doc`

