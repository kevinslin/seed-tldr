---
id: common.cppclean
title: Cppclean
desc: ''
updated: 1642441815004
created: 1642441815004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cppclean

> Find unused code in C++ projects.
> More information: <https://github.com/myint/cppclean>.

- Run in a project's directory:

`cppclean {{path/to/project}}`

- Run on a project where the headers are in the `inc1/` and `inc2/` directories:

`cppclean {{path/to/project}} --include-path={{inc1}} --include-path={{inc2}}`

- Run on a specific file `main.cpp`:

`cppclean {{main.cpp}}`

- Run on the current directory, excluding the "build" directory:

`cppclean {{.}} --exclude={{build}}`

