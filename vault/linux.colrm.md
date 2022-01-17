---
id: linux.colrm
title: Colrm
desc: ''
updated: 1642441815091
created: 1642441815091
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# colrm

> Remove columns from stdin.
> More information: <https://manned.org/colrm>.

- Remove first column of stdin:

`colrm {{1 1}}`

- Remove from 3rd column till the end of each line:

`colrm {{3}}`

- Remove from the 3rd column till the 5th column of each line:

`colrm {{3 5}}`

