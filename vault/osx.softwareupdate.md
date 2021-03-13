---
id: osx.softwareupdate
title: Softwareupdate
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# softwareupdate

> A tool for updating MacOS App Store apps via the command line.

- List all available updates:

`softwareupdate -l`

- Download and install all updates:

`softwareupdate -ia`

- Download and install all recommended updates:

`softwareupdate -ir`

- Download and install a specific app:

`softwareupdate -i {{update_name}}`

