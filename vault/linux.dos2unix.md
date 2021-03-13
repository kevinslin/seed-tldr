---
id: linux.dos2unix
title: Dos2unix
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dos2unix

> Change DOS-style line endings to Unix-style.
> Replaces CRLF with CR.

- Change the line endings of a file:

`dos2unix {{filename}}`

- Create a copy with Unix-style line endings:

`dos2unix -n {{filename}} {{new_filename}}`

