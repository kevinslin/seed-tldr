---
id: common.strings
title: Strings
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# strings

> Find printable strings in an object file or binary.

- Print all strings in a binary:

`strings {{file}}`

- Limit results to strings at least _length_ characters long:

`strings -n {{length}} {{file}}`

- Prefix each result with its offset within the file:

`strings -t d {{file}}`

- Prefix each result with its offset within the file in hexadecimal:

`strings -t x {{file}}`

