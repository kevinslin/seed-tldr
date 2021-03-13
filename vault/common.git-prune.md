---
id: common.git-prune
title: Git Prune
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git prune

> Git command for pruning all unreachable objects from the object database.
> This command is often not used directly but as an internal command that is used by Git gc.
> More information: <https://git-scm.com/docs/git-prune>.

- Report what would be removed by Git prune without removing it:

`git prune --dry-run`

- Prune unreachable objects and display what has been pruned to stdout:

`git prune --verbose`

- Prune unreachable objects while showing progress:

`git prune --progress`

