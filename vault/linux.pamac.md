---
id: linux.pamac
title: Pamac
desc: ''
updated: 1615663978751
created: 1615663978751
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pamac

> A command line utility for the GUI package manager pamac.

- Install a new package:

`pamac install {{package_name}}`

- Remove a package and its no longer required dependencies (orphans):

`pamac remove -o {{package_name}}`

- Search the package database for a package:

`pamac search {{package_name}}`

- List installed packages:

`pamac list -i`

- Check for package updates:

`pamac checkupdates`

