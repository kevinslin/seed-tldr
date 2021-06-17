---
id: common.fortune
title: Fortune
desc: ''
updated: 1623965306184
created: 1623965306184
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fortune

> Print a random quotation (fortune-cookie style).
> More information: <https://man.archlinux.org/man/fortune.6>.

- Print a quotation:

`fortune`

- Print an offensive quotation:

`fortune -o`

- Print a long quotation:

`fortune -l`

- Print a short quotation:

`fortune -s`

- List the available quotation database files:

`fortune -f`

- Print a quotation from one of the database files listed by `fortune -f`:

`fortune {{filename}}`

