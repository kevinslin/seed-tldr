---
id: linux.paru
title: Paru
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# paru

> An AUR helper and pacman wrapper.
> More information: <https://github.com/Morganamilo/paru>.

- Interactively search for and install a package:

`paru {{package_name_or_seach_term}}`

- Synchronize and update all packages:

`paru`

- Upgrade AUR packages:

`paru -Sua`

- Get information about a package:

`paru -Si {{package_name}}`

- Download `PKGBUILD` and other package source files from the AUR or ABS:

`paru --getpkgbuild {{package_name}}`

- Display the `PKGBUILD` file of a package:

`paru --getpkgbuild --print {{package_name}}`

