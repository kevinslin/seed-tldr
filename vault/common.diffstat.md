---
id: common.diffstat
title: Diffstat
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# diffstat

> Create a histogram from the output of the `diff` command.

- Display changes in a histogram:

`diff {{file1}} {{file2}} | diffstat`

- Display inserted, deleted and modified changes as a table:

`diff {{file1}} {{file2}} | diffstat -t`

