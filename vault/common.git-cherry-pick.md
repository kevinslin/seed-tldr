---
id: common.git-cherry-pick
title: Git Cherry Pick
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git cherry-pick

> Apply the changes introduced by existing commits to the current branch.
> To apply changes to another branch, first use `git checkout` to switch to the desired branch.
> More information: <https://git-scm.com/docs/git-cherry-pick>.

- Apply a commit to the current branch:

`git cherry-pick {{commit}}`

- Apply a range of commits to the current branch (see also `git rebase --onto`):

`git cherry-pick {{start_commit}}~..{{end_commit}}`

- Apply multiple (non-sequential) commits to the current branch:

`git cherry-pick {{commit_1}} {{commit_2}}`

- Add the changes of a commit to the working directory, without creating a commit:

`git cherry-pick -n {{commit}}`

