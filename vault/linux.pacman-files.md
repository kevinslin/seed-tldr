---
id: linux.pacman-files
title: Pacman Files
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pacman --files

> Arch Linux package manager utility.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

`pacman --files --help`

- Update the package database:

`sudo pacman --files --refresh`

- Find the package that owns a specific file:

`pacman --files {{filename}}`

- Find the package that owns a specific file, using a regular expression:

`pacman --files --regex '{{search_pattern}}'`

- List only the package names:

`pacman --files --quite {{filename}}`

- List the files owned by a specific package:

`pacman --files --list {{package_name}}`

- List only the absolute path to the files:

`pacman --query --list --quite {{package_name}}`

