---
id: linux.guix-package
title: Guix Package
desc: ''
updated: 1615655543102
created: 1615655543102
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

