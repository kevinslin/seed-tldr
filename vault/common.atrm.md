---
id: common.atrm
title: Atrm
desc: ''
updated: 1646802118602
created: 1646802118602
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atrm

> Remove jobs scheduled by `at` or `batch` commands.
> To find job numbers use `atq`.
> More information: <https://manned.org/atrm>.

- Remove job number 10:

`atrm {{10}}`

- Remove many jobs, separated by spaces:

`atrm {{15}} {{17}} {{22}}`

