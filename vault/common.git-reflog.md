---
id: common.git-reflog
title: Git Reflog
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git reflog

> Show a log of changes to local references like HEAD, branches or tags.
> More information: <https://git-scm.com/docs/git-reflog>.

- Show the reflog for HEAD:

`git reflog`

- Show the reflog for a given branch:

`git reflog {{branch_name}}`

- Show only the 5 latest entries in the reflog:

`git reflog -n {{5}}`

