---
id: linux.hexdump
title: Hexdump
desc: ''
updated: 1615663978747
created: 1615663978747
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hexdump

> An ASCII, decimal, hexadecimal, octal dump.

- Print the hexadecimal representation of a file:

`hexdump {{file}}`

- Display the input offset in hexadecimal and its ASCII representation in two columns:

`hexdump -C {{file}}`

- Display the hexadecimal representation of a file, but interpret only n bytes of the input:

`hexdump -C -n{{number_of_bytes}} {{file}}`

