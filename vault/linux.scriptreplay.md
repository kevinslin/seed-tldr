---
id: linux.scriptreplay
title: Scriptreplay
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# scriptreplay

> Replay a typescript created by the `script` command to the standard output.

- Replay a typescript at the speed it was recorded:

`scriptreplay {{path/to/timing_file}} {{path/to/typescript}}`

- Replay a typescript at double the original speed:

`scriptreplay {{path/to/timingfile}} {{path/to/typescript}} 2`

- Replay a typescript at half the original speed:

`scriptreplay {{path/to/timingfile}} {{path/to/typescript}} 0.5`

