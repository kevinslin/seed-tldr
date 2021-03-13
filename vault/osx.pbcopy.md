---
id: osx.pbcopy
title: Pbcopy
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pbcopy

> Place standard output in the clipboard.

- Place the contents of a file in the clipboard:

`pbcopy < {{file}}`

- Place the results of a command in the clipboard:

`find . -type t -name "*.png" | pbcopy`

