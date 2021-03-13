---
id: common.base32
title: Base32
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# base32

> Encode or decode file or standard input to/from Base32, to standard output.

- Encode a file:

`base32 {{filename}}`

- Decode a file:

`base32 --decode {{filename}}`

- Encode from stdin:

`{{somecommand}} | base32`

- Decode from stdin:

`{{somecommand}} | base32 --decode`

