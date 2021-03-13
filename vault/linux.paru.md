---
id: linux.paru
title: Paru
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# paru

> An AUR helper and pacman wrapper.
> More information: <https://github.com/morganamilo/paru>.

- Interactively search for and install a package:

`paru {{package_name_or_seach_term}}`

- Synchronize and update all packages:

`paru`

- Upgrade AUR packages:

`paru -Sua`

- Get information about a package:

`paru -Si {{package_name}}`

- Show statistics for installed packages and system health:

`paru -P --stats`

