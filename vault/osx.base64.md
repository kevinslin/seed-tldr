---
id: osx.base64
title: Base64
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# base64

> Encode and decode using Base64 representation.

- Encode a file:

`base64 --input={{plain_file}}`

- Decode a file:

`base64 --decode --input={{base64_file}}`

- Encode from stdin:

`echo -n {{plain_text}} | base64`

- Decode from stdin:

`echo -n {{base64_text}} | base64 --decode`

