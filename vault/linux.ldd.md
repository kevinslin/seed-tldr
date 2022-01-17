---
id: linux.ldd
title: Ldd
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ldd

> Display shared library dependencies.
> More information: <https://manned.org/ldd>.

- Display shared library dependencies of a binary:

`ldd {{path/to/binary}}`

- Display unused direct dependencies:

`ldd -u {{path/to/binary}}`

