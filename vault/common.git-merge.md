---
id: common.git-merge
title: Git Merge
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git merge

> Merge branches.
> More information: <https://git-scm.com/docs/git-merge>.

- Merge a branch into your current branch:

`git merge {{branch_name}}`

- Edit the merge message:

`git merge -e {{branch_name}}`

- Merge a branch and create a merge commit:

`git merge --no-ff {{branch_name}}`

- Abort a merge in case of conflicts:

`git merge --abort`

