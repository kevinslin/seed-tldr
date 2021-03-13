---
id: common.git-update-ref
title: Git Update Ref
desc: ''
updated: 1615655543060
created: 1615655543060
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git update-ref

> Git command for creating, updating, and deleting Git refs.
> More information: <https://git-scm.com/docs/git-update-ref>.

- Delete a ref, useful for soft resetting the first commit:

`git update-ref -d {{HEAD}}`

- Update ref with a message:

`git update-ref -m {{message}} {{HEAD}} {{4e95e05}}`

