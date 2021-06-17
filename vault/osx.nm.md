---
id: osx.nm
title: Nm
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nm

> List symbol names in object files.

- List global (extern) functions in a file (prefixed with T):

`nm -g {{file.o}}`

- List only undefined symbols in a file:

`nm -u {{file.o}}`

- List all symbols, even debugging symbols:

`nm -a {{file.o}}`

- Demangle C++ symbols (make them readable):

`nm -demangle {{file.o}}`

