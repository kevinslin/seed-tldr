---
id: common.nim
title: Nim
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

