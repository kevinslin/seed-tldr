---
id: linux.guix-package
title: Guix Package
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# guix package

> Install, upgrade and remove Guix packages, or rollback to previous configurations.

- Install a new package:

`guix package -i {{package_name}}`

- Remove a package:

`guix package -r {{package_name}}`

- Search the package database for a regular expression:

`guix package -s "{{search_pattern}}"`

- List installed packages:

`guix package -I`

- List generations:

`guix package -l`

- Roll back to the previous generation:

`guix package --roll-back`

