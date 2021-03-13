---
id: common.cryfs
title: Cryfs
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cryfs

> A cryptographic filesystem for the cloud.
> More information: <https://www.cryfs.org/>.

- Mount an encrypted filesystem. The initialization wizard will be started on the first execution:

`cryfs {{path/to/cipher_dir}} {{path/to/mount_point}}`

- Unmount an encrypted filesystem:

`cryfs-unmount {{path/to/mount_point}}`

- Automatically unmount after ten minutes of inactivity:

`cryfs --unmount-idle {{10}} {{path/to/cipher_dir}} {{path/to/mount_point}}`

- Show a list of supported ciphers:

`cryfs --show-ciphers`

