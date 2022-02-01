---
id: common.ar
title: Ar
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ar

> Create, modify, and extract from archives (`.a`, `.so`, `.o`).
> More information: <https://manned.org/ar>.

- Extract all members from an archive:

`ar -x {{path/to/file.a}}`

- List the members of an archive:

`ar -t {{path/to/file.a}}`

- Replace or add files to an archive:

`ar -r {{path/to/file.a}} {{path/to/file1.o}} {{path/to/file2.o}}`

- Insert an object file index (equivalent to using `ranlib`):

`ar -s {{path/to/file.a}}`

- Create an archive with files and an accompanying object file index:

`ar -rs {{path/to/file.a}} {{path/to/file1.o}} {{path/to/file2.o}}`

