---
id: common.tac
title: Tac
desc: ''
updated: 1615655543088
created: 1615655543088
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# tac

> Print and concatenate files in reverse (last line first).

- Print the contents of _file1_ reversed to the standard output:

`tac {{file1}}`

- Print the contents of the standard input reversed to the standard output:

`{{command}} | tac`

- Concatenate several files reversed into the target file:

`tac {{file1}} {{file2}} > {{target_file}}`

