---
id: osx.mdfind
title: Osx
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mdfind

> List files matching a given query.

- Find a file by its name:

`mdfind -name {{file}}`

- Find a file by its content:

`mdfind {{query}}`

- Find a file containing a string, in a given directory:

`mdfind -onlyin {{directory}} {{query}}`

