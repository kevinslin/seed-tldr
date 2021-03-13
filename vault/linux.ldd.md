---
id: linux.ldd
title: Ldd
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ldd

> Display shared library dependencies.

- Display shared library dependencies of a binary:

`ldd {{path/to/binary}}`

- Display unused direct dependencies:

`ldd -u {{path/to/binary}}`

