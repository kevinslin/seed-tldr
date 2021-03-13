---
id: osx.pbcopy
title: Pbcopy
desc: ''
updated: 1615663978760
created: 1615663978760
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

