---
id: common.rustc
title: Rustc
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
# rustc

> The Rust compiler.
> Processes, compiles and links Rust language source files.
> More information: <https://doc.rust-lang.org/rustc>.

- Compile a single file:

`rustc {{file.rs}}`

- Compile with high optimization:

`rustc -O {{file.rs}}`

- Compile with debugging information:

`rustc -g {{file.rs}}`

- Compile with architecture-specific optimizations for the current CPU:

`rustc -C target-cpu=native {{path/to/file.rs}}`

- Display architecture-specific optimizations for the current CPU:

`rustc -C target-cpu=native --print cfg`

- Display target list:

`rustc --print target-list`

- Compile for a specific target:

`rustc --target {{target_triple}} {{path/to/file.rs}}`

