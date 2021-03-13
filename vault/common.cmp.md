---
id: common.cmp
title: Cmp
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cmp

> Compare two files.

- Find the byte number and line number of the first difference between the files:

`cmp {{file1}} {{file2}}`

- Find the byte number and differing bytes of every difference:

`cmp -l {{file1}} {{file2}}`

