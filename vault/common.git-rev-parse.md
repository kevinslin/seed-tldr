---
id: common.git-rev-parse
title: Git Rev Parse
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git rev-parse

> Display metadata related to specific revisions.
> More information: <https://git-scm.com/docs/git-rev-parse>.

- Get the commit hash of a branch:

`git rev-parse {{branch_name}}`

- Get the current branch name:

`git rev-parse --abbrev-ref {{HEAD}}`

- Get the absolute path to the root directory:

`git rev-parse --show-toplevel`

