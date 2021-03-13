---
id: common.paste
title: Paste
desc: ''
updated: 1615655543077
created: 1615655543077
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# paste

> Merge lines of files.

- Join all the lines into a single line, using TAB as delimiter:

`paste -s {{file}}`

- Join all the lines into a single line, using the specified delimiter:

`paste -s -d {{delimiter}} {{file}}`

- Merge two files side by side, each in its column, using TAB as delimiter:

`paste {{file1}} {{file2}}`

- Merge two files side by side, each in its column, using the specified delimiter:

`paste -d {{delimiter}} {{file1}} {{file2}}`

- Merge two files, with lines added alternatively:

`paste -d '\n' {{file1}} {{file2}}`

