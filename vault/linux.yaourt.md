---
id: linux.yaourt
title: Yaourt
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# yaourt

> Arch Linux utility for building packages from the Arch User Repository.

- Synchronize and update all packages (including AUR):

`yaourt -Syua`

- Install a new package (includes AUR):

`yaourt -S {{package_name}}`

- Remove a package and its dependencies (includes AUR packages):

`yaourt -Rs {{package_name}}`

- Search the package database for a keyword (including AUR):

`yaourt -Ss {{package_name}}`

- List installed packages, versions, and repositories (AUR packages will be listed under the repository name 'local'):

`yaourt -Q`

