---
id: common.sum
title: Sum
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# sum

> Compute checksums and the number of blocks for a file.
> A predecessor to the more modern `cksum`.

- Compute a checksum with BSD-compatible algorithm and 1024-byte blocks:

`sum {{file}}`

- Compute a checksum with System V-compatible algorithm and 512-byte blocks:

`sum --sysv {{file}}`

