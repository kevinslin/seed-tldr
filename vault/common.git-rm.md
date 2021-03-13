---
id: common.git-rm
title: Git Rm
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git rm

> Remove files from repository index and local filesystem.
> More information: <https://git-scm.com/docs/git-rm>.

- Remove file from repository index and filesystem:

`git rm {{file}}`

- Remove directory:

`git rm -r {{directory}}`

- Remove file from repository index but keep it untouched locally:

`git rm --cached {{file}}`

