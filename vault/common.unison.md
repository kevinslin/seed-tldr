---
id: common.unison
title: Unison
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# unison

> Bidirectional file synchronisation tool.
> More information: <https://www.cis.upenn.edu/~bcpierce/unison/download/releases/stable/unison-manual.html>.

- Sync two directories (creates log first time these two directories are synchronised):

`unison {{path/to/directory_1}} {{path/to/directory_2}}`

- Automatically accept the (non-conflicting) defaults:

`unison {{path/to/directory_1}} {{path/to/directory_2}} -auto`

- Ignore some files using a pattern:

`unison {{path/to/directory_1}} {{path/to/directory_2}} -ignore {{pattern}}`

- Show documentation:

`unison -doc {{topics}}`

