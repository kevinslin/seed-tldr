---
id: windows.choco-pin
title: Choco Pin
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco pin

> Pin a package at a specific version with Chocolatey.
> Pinned packages are skipped automatically when upgrading.
> More information: <https://chocolatey.org/docs/commands-pin>.

- Display a list of pinned packages and their versions:

`choco pin list`

- Pin a package at its current version:

`choco pin add --name {{package}}`

- Pin a package at a specific version:

`choco pin add --name {{package}} --version {{version}}`

- Remove a pin for a specific package:

`choco pin remove --name {{package}}`

