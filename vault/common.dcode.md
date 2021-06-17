---
id: common.dcode
title: Dcode
desc: ''
updated: 1623965016118
created: 1623965016118
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dcode

> Recursively detect and decode strings, supporting hex, decimal, binary, base64, URL, FromChar encodings, Caesar ciphers, and MD5, SHA1, and SHA2 hashes.
> Warning: uses 3rd-party web services for MD5, SHA1 and SHA2 hash lookups. For sensitive data, use `-s` to avoid these services.
> More information: <https://github.com/s0md3v/Decodify>.

- Recursively detect and decode a string:

`dcode "{{NjM3YTQyNzQ1YTQ0NGUzMg==}}"`

- Rotate a string by the specified offset:

`dcode -rot {{11}} "{{spwwz hzcwo}}"`

- Rotate a string by all 26 possible offsets:

`dcode -rot {{all}} "{{bpgkta xh qtiitg iwpc sr}}"`

- Reverse a string:

`dcode -rev "{{hello world}}"`

