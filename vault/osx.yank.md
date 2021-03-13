---
id: osx.yank
title: Yank
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yank

> Read input from stdin and display a selection interface that allows a field to be selected and copied to the clipboard.

- Yank using the default delimiters (\\f, \\n, \\r, \\s, \\t):

`{{sudo dmesg}} | yank`

- Yank an entire line:

`{{sudo dmesg}} | yank -l`

- Yank using a specific delimiter:

`{{echo hello=world}} | yank -d {{=}}`

- Only yank fields matching a specific pattern:

`{{ps ux}} | yank -g "{{[0-9]+}}"`

