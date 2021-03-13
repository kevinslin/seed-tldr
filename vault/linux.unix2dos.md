---
id: linux.unix2dos
title: Unix2dos
desc: ''
updated: 1615655543110
created: 1615655543110
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# unix2dos

> Change Unix-style line endings to DOS-style.
> Replaces CR with CRLF.

- Change the line endings of a file:

`unix2dos {{filename}}`

- Create a copy with DOS-style line endings:

`unix2dos -n {{filename}} {{new_filename}}`

