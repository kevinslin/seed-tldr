---
id: common.rr
title: Rr
desc: ''
updated: 1615655543082
created: 1615655543082
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rr

> Debugging tool designed to record and replay program execution.
> More information: <https://rr-project.org/>.

- Record an application:

`rr record {{path/to/binary --arg1 --arg2}}`

- Replay latest recorded execution:

`rr replay`

