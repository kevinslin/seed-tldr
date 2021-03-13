---
id: common.nice
title: Nice
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nice

> Execute a program with a custom scheduling priority (niceness).
> Niceness values range from -20 (the highest priority) to 19 (the lowest).

- Launch a program with altered priority:

`nice -n {{niceness_value}} {{command}}`

