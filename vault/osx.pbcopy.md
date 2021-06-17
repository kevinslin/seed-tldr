---
id: osx.pbcopy
title: Pbcopy
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pbcopy

> Place standard output in the clipboard.

- Place the contents of a file in the clipboard:

`pbcopy < {{file}}`

- Place the results of a command in the clipboard:

`find . -type t -name "*.png" | pbcopy`

