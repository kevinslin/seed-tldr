---
id: common.base64
title: Base64
desc: ''
updated: 1615663978700
created: 1615663978700
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# base64

> Encode or decode file or standard input to/from Base64, to standard output.

- Encode a file:

`base64 {{filename}}`

- Decode a file:

`base64 --decode {{filename}}`

- Encode from stdin:

`{{somecommand}} | base64`

- Decode from stdin:

`{{somecommand}} | base64 --decode`

