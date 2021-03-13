---
id: common.git-branch
title: Git Branch
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git branch

> Main Git command for working with branches.
> More information: <https://git-scm.com/docs/git-branch>.

- List local branches. The current branch is highlighted by `*`:

`git branch`

- List all branches (local and remote):

`git branch -a`

- Show the name of the current branch:

`git branch --show-current`

- Create new branch based on the current commit:

`git branch {{branch_name}}`

- Create new branch based on a specific commit:

`git branch {{branch_name}} {{commit_hash}}`

- Rename a branch (must not have it checked out to do this):

`git branch -m {{old_branch_name}} {{new_branch_name}}`

- Delete a local branch (must not have it checked out to do this):

`git branch -d {{branch_name}}`

- Delete a remote branch:

`git push {{remote_name}} --delete {{remote_branch_name}}`

