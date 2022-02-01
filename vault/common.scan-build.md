---
id: common.scan-build
title: Scan Build
desc: ''
updated: 1642574149010
created: 1642574149010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scan-build

> Command-line utility to run a static analyzer over a codebase as part of performing a regular build.
> More information: <https://clang-analyzer.llvm.org/scan-build.html>.

- Build and analyze the project in the current directory:

`scan-build {{make}}`

- Run a command and pass all subsequent options to it:

`scan-build {{command}} {{command_arguments}}`

- Display help:

`scan-build`

