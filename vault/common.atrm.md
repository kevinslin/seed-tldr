---
id: common.atrm
title: Atrm
desc: ''
updated: 1642441814995
created: 1642441814995
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
> More information: <https://man.archlinux.org/man/at.1>.

- Remove job number 10:

`atrm {{10}}`

- Remove many jobs, separated by spaces:

`atrm {{15}} {{17}} {{22}}`

