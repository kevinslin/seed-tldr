---
id: linux.pkginfo
title: Pkginfo
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkginfo

> Query the package database on a CRUX system.
> More information: <https://crux.nu/Main/Handbook3-6#ntoc19>.

- List installed packages and their versions:

`pkginfo -i`

- List files owned by a package:

`pkginfo -l {{package_name}}`

- List the owner(s) of files matching a pattern:

`pkginfo -o {{pattern}}`

- Print the footprint of a file:

`pkginfo -f {{file}}`

