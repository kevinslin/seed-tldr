---
id: common.cradle-package
title: Cradle Package
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cradle package

> Manage packages for a Cradle instance.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#package>.

- Display a list of available packages:

`cradle package list`

- Search for a package:

`cradle package search {{package}}`

- Install a package from Packagist:

`cradle package install {{package}}`

- Install a specific version of a package:

`cradle package install {{package}} {{version}}`

- Update a package:

`cradle package update {{package}}`

- Update a package to a specific version:

`cradle package update {{package}} {{version}}`

- Remove a specific package:

`cradle package remove {{package}}`

