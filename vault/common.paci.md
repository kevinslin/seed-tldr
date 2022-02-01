---
id: common.paci
title: Paci
desc: ''
updated: 1642441815055
created: 1642441815055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# paci

> A package manager for Bash scripts.
> More information: <https://github.com/tradebyte/paci>.

- Update the list of available packages and versions (it's recommended to run this before other `paci` commands):

`paci refresh`

- Configure its behaviour:

`paci configure`

- Search for a given package:

`paci search {{package}}`

- Install a package:

`paci install {{package}}`

- Update a package:

`paci update {{package}}`

