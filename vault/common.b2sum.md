---
id: common.b2sum
title: B2sum
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# b2sum

> Calculate BLAKE2 cryptographic checksums.
> More information: <https://blake2.net/#su>.

- Calculate the BLAKE2 checksum for a file:

`b2sum {{filename1}}`

- Calculate BLAKE2 checksums for multiple files:

`b2sum {{filename1}} {{filename2}}`

- Read a file of BLAKE2 sums and filenames and verify all files have matching checksums:

`b2sum -c {{filename.b2}}`

- Calculate the BLAKE2 checksum from stdin:

`{{somecommand}} | b2sum`

