---
id: common.cargo-doc
title: Cargo Doc
desc: ''
updated: 1642441815001
created: 1642441815001
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cargo doc

> Build and view Rust package documentation offline.
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-doc.html>.

- Build and view the default package documentation in the browser:

`cargo doc --open`

- Build documentation without accessing the network:

`cargo doc --offline`

- View a particular package's documentation:

`cargo doc --open --package {{package}}`

- View a particular package's documentation offline:

`cargo doc --open --offline --package {{package}}`

