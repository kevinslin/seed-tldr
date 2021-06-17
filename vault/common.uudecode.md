---
id: common.uudecode
title: Uudecode
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uudecode

> Decode files encoded by `uuencode`.
> More information: <https://manned.org/uudecode>.

- Decode a file that was encoded with `uuencode` and print the result to stdout:

`uudecode {{path/to/encoded_file}}`

- Decode a file that was encoded with `uuencode` and write the result to a file:

`uudecode -o {{path/to/decoded_file}} {{path/to/encoded_file}}`

