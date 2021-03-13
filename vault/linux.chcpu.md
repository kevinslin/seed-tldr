---
id: linux.chcpu
title: Chcpu
desc: ''
updated: 1615655543096
created: 1615655543096
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# chcpu

> Enable/disable a system's CPUs.

- Disable CPUs via a list of CPU ID numbers:

`chcpu -d {{1,3}}`

- Enable a set of CPUs via a range of CPU ID numbers:

`chcpu -e {{1-10}}`

