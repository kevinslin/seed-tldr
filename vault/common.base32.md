---
id: common.base32
title: Base32
desc: ''
updated: 1615663978700
created: 1615663978700
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# base32

> Encode or decode file or standard input to/from Base32, to standard output.

- Encode a file:

`base32 {{filename}}`

- Decode a file:

`base32 --decode {{filename}}`

- Encode from stdin:

`{{somecommand}} | base32`

- Decode from stdin:

`{{somecommand}} | base32 --decode`

