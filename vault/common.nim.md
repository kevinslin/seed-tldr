---
id: common.nim
title: Nim
desc: ''
updated: 1615663978726
created: 1615663978726
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nim

> The Nim compiler.
> Processes, compiles and links Nim language source files.
> More information: <https://nim-lang.org>.

- Compile a source file:

`nim compile {{file.nim}}`

- Compile and run a source file:

`nim compile -r {{file.nim}}`

- Compile a source file with release optimizations enabled:

`nim compile -d:release {{file.nim}}`

- Build a release binary optimized for low file size:

`nim compile -d:release --opt:size {{file.nim}}`

- Generate HTML documentation for a module (output will be placed in the current directory):

`nim doc {{file.nim}}`
