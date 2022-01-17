---
id: common.ctest
title: Ctest
desc: ''
updated: 1642441815006
created: 1642441815006
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ctest

> CMake test driver program.
> More information: <https://gitlab.kitware.com/cmake/community/wikis/doc/ctest/Testing-With-CTest>.

- Run all tests defined in the CMake project, executing 4 jobs at a time in parallel:

`ctest -j{{4}} --output-on-failure`

- Show a list of available tests:

`ctest -N`

- Run a single test based on its name, or filter on a regular expression:

`ctest --output-on-failure -R '^{{test_name}}$'`

