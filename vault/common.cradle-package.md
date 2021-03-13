---
id: common.cradle-package
title: Cradle Package
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cradle package

> Manage packages for a Cradle instance.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#package>.

- Display a list of available packages:

`cradle package list`

- Search for a package:

`cradle package search {{package}}`

- Install a package from Packagist:

`cradle package install {{package}}`

- Install a specific version of a package:

`cradle package install {{package}} {{version}}`

- Update a package:

`cradle package update {{package}}`

- Update a package to a specific version:

`cradle package update {{package}} {{version}}`

- Remove a specific package:

`cradle package remove {{package}}`

