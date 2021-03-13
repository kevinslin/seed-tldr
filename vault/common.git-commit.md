---
id: common.git-commit
title: Git Commit
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git commit

> Commit files to the repository.
> More information: <https://git-scm.com/docs/git-commit>.

- Commit staged files to the repository with a message:

`git commit -m {{message}}`

- Auto stage all modified files and commit with a message:

`git commit -a -m {{message}}`

- Update the last commit by adding the currently staged changes, changing the commit's hash:

`git commit --amend`

- Commit only specific (already staged) files:

`git commit {{path/to/my/file1}} {{path/to/my/file2}}`

