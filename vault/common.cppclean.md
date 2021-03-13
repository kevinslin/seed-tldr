---
id: common.cppclean
title: Cppclean
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

