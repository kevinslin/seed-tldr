---
id: common.for
title: For
desc: ''
updated: 1615655543055
created: 1615655543055
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# for

> Shell loop over parameters.

- Perform a command with different arguments:

`for argument in 1 2 3; do {{command $argument}}; done`

- Perform a command in every directory:

`for d in *; do (cd $d; {{command}}); done`

