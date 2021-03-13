---
id: common.base64
title: Base64
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# base64

> Encode or decode file or standard input to/from Base64, to standard output.

- Encode a file:

`base64 {{filename}}`

- Decode a file:

`base64 --decode {{filename}}`

- Encode from stdin:

`{{somecommand}} | base64`

- Decode from stdin:

`{{somecommand}} | base64 --decode`

