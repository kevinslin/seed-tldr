---
id: linux.trizen
title: Trizen
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trizen

> Arch Linux utility for building packages from the Arch User Repository (AUR).

- Synchronize and update all AUR packages:

`trizen -Syua`

- Install a new package:

`trizen -S {{package}}`

- Remove a package and its dependencies:

`trizen -Rs {{package}}`

- Search the package database for a keyword:

`trizen -Ss {{keyword}}`

- Show information about a package:

`trizen -Si {{package}}`

- List installed packages and versions:

`trizen -Qe`

