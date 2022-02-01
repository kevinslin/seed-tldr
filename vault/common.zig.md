---
id: common.zig
title: Zig
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zig

> The Zig compiler and toolchain.
> More information: <https://ziglang.org>.

- Compile the project in the current directory:

`zig build`

- Compile and run the project in the current directory:

`zig build run`

- Initialize a `zig build` application:

`zig init-exe`

- Intitialize a `zig build` library:

`zig init-lib`

- Create and run a test build:

`zig test {{path/to/file.zig}}`

- Reformat Zig source into canonical form:

`zig fmt {{path/to/file.zig}}`

- Use Zig as a drop-in C compiler:

`zig cc {{path/to/file.c}}`

- Use Zig as a drop-in C++ compiler:

`zig c++ {{path/to/file.cpp}}`

