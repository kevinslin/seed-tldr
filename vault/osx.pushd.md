---
id: osx.pushd
title: Pushd
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pushd

> Place a directory on a stack so it can be accessed later.
> See also `popd` to switch back to original directory.

- Switch to directory and push it on the stack:

`pushd {{directory}}`

- Switch first and second directories on the stack:

`pushd`

- Rotate stack by making the 5th element the top of the stack:

`pushd +4`

