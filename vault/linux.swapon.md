---
id: linux.swapon
title: Swapon
desc: ''
updated: 1615655543110
created: 1615655543110
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# swapon

> Enables device or file for swapping.

- Get swap information:

`swapon -s`

- Enable a given swap partition:

`swapon {{/dev/sdb7}}`

- Enable a given swap file:

`swapon {{path/to/file}}`

- Enable all swap areas:

`swapon -a`

- Enable swap by label of a device or file:

`swapon -L {{swap1}}`

