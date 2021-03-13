---
id: common.git-status
title: Git Status
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git status

> Show the changes to files in a Git repository.
> Lists changed, added and deleted files compared to the currently checked-out commit.
> More information: <https://git-scm.com/docs/git-status>.

- Show changed files which are not yet added for commit:

`git status`

- Give output in [s]hort format:

`git status -s`

- Don't show untracked files in the output:

`git status --untracked-files=no`

- Show output in [s]hort format along with [b]ranch info:

`git status -sb`

