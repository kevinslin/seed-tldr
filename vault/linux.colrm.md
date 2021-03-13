---
id: linux.colrm
title: Colrm
desc: ''
updated: 1615663978742
created: 1615663978742
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# colrm

> Remove columns from stdin.

- Remove first column of stdin:

`colrm {{1 1}}`

- Remove from 3rd column till the end of each line:

`colrm {{3}}`

- Remove from the 3rd column till the 5th column of each line:

`colrm {{3 5}}`

