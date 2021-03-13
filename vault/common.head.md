---
id: common.head
title: Head
desc: ''
updated: 1615655543062
created: 1615655543062
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# head

> Output the first part of files.

- Output the first few lines of a file:

`head -n {{count_of_lines}} {{filename}}`

- Output the first few bytes of a file:

`head -c {{size_in_bytes}} {{filename}}`

- Output everything but the last few lines of a file:

`head -n -{{count_of_lines}} {{filename}}`

- Output everything but the last few bytes of a file:

`head -c -{{size_in_bytes}} {{filename}}`

