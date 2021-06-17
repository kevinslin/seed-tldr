---
id: linux.pkginfo
title: Pkginfo
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkginfo

> Query the package database on a CRUX system.

- List installed packages and their versions:

`pkginfo -i`

- List files owned by a package:

`pkginfo -l {{package_name}}`

- List the owner(s) of files matching a pattern:

`pkginfo -o {{pattern}}`

- Print the footprint of a file:

`pkginfo -f {{file}}`

