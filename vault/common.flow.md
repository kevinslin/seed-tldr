---
id: common.flow
title: Flow
desc: ''
updated: 1615655543055
created: 1615655543055
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# flow

> A static type checker for JavaScript.
> More information: <https://flow.org>.

- Run a flow check:

`flow`

- Check which files are being checked by flow:

`flow ls`

- Run a type coverage check on all files in a directory:

`flow batch-coverage --show-all --strip-root {{path/to/directory}}`

- Display line-by-line type coverage stats:

`flow coverage --color {{path/to/file.jsx}}`

