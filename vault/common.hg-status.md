---
id: common.hg-status
title: Hg Status
desc: ''
updated: 1615655543062
created: 1615655543062
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# hg status

> Show files that have changed in the working directory.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#status>.

- Display the status of changed files:

`hg status`

- Display only modified files:

`hg status --modified`

- Display only added files:

`hg status --added`

- Display only removed files:

`hg status --removed`

- Display only deleted (but tracked) files:

`hg status --deleted`

- Display changes in the working directory compared to a specified changeset:

`hg status --rev {{revision}}`

- Display only files matching a specified glob pattern:

`hg status --include {{pattern}}`

- Display files, excluding those that match a specified glob pattern:

`hg status --exclude {{pattern}}`

