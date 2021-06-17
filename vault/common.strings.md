---
id: common.strings
title: Strings
desc: ''
updated: 1623965016151
created: 1623965016151
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# strings

> Find printable strings in an object file or binary.

- Print all strings in a binary:

`strings {{file}}`

- Limit results to strings at least _length_ characters long:

`strings -n {{length}} {{file}}`

- Prefix each result with its offset within the file:

`strings -t d {{file}}`

- Prefix each result with its offset within the file in hexadecimal:

`strings -t x {{file}}`

