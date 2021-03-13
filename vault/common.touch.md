---
id: common.touch
title: Touch
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# touch

> Change a file access and modification times (atime, mtime).

- Create a new empty file(s) or change the times for existing file(s) to current time:

`touch {{filename}}`

- Set the times on a file to a specific date and time:

`touch -t {{YYYYMMDDHHMM.SS}} {{filename}}`

- Use the times from a file to set the times on a second file:

`touch -r {{filename}} {{filename2}}`

