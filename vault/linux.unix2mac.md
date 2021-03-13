---
id: linux.unix2mac
title: Unix2mac
desc: ''
updated: 1615655543110
created: 1615655543110
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# unix2mac

> Change Unix-style line endings to macOS-style.
> Replaces CR with LF.

- Change the line endings of a file:

`unix2mac {{filename}}`

- Create a copy with macOS-style line endings:

`unix2mac -n {{filename}} {{new_filename}}`

