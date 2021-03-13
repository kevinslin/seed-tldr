---
id: common.stdbuf
title: Stdbuf
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# stdbuf

> Run a command with modified buffering operations for its standard streams.

- Change the standard input buffer size to 512 KiB:

`stdbuf --input={{512K}} {{command}}`

- Change the standard output buffer to line-buffered:

`stdbuf --output={{L}} {{command}}`

- Change the standard error buffer to unbuffered:

`stdbuf --error={{0}} {{command}}`

