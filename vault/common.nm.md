---
id: common.nm
title: Nm
desc: ''
updated: 1644840636172
created: 1644840636172
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nm

> List symbol names in object files.
> More information: <https://manned.org/nm>.

- List global (extern) functions in a file (prefixed with T):

`nm -g {{path/to/file.o}}`

- List only undefined symbols in a file:

`nm -u {{path/to/file.o}}`

- List all symbols, even debugging symbols:

`nm -a {{path/to/file.o}}`

- Demangle C++ symbols (make them readable):

`nm --demangle {{path/to/file.o}}`

