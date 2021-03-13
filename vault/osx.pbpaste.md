---
id: osx.pbpaste
title: Pbpaste
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pbpaste

> Send the contents of the clipboard to standard output.

- Write the contents of the clipboard to a file:

`pbpaste > {{file}}`

- Use the contents of the clipboard as input to a command:

`pbpaste | grep foo`

