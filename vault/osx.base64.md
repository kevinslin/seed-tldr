---
id: osx.base64
title: Base64
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# base64

> Encode and decode using Base64 representation.

- Encode a file:

`base64 --input={{plain_file}}`

- Decode a file:

`base64 --decode --input={{base64_file}}`

- Encode from stdin:

`echo -n {{plain_text}} | base64`

- Decode from stdin:

`echo -n {{base64_text}} | base64 --decode`

