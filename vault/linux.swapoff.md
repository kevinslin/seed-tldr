---
id: linux.swapoff
title: Swapoff
desc: ''
updated: 1615655543110
created: 1615655543110
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# swapoff

> Disables device or file for swapping.

- Disable a given swap partition:

`swapoff {{/dev/sdb7}}`

- Disable a given swap file:

`swapoff {{path/to/file}}`

- Disable all swap areas:

`swapoff -a`

- Disable swap by label of a device or file:

`swapoff -L {{swap1}}`

