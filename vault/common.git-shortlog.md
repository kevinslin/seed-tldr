---
id: common.git-shortlog
title: Git Shortlog
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git shortlog

> Summarizes the `git log` output.
> More information: <https://git-scm.com/docs/git-shortlog>.

- View a summary of all the commits made, grouped alphabetically by author name:

`git shortlog`

- View a summary of all the commits made, sorted by the number of commits made:

`git shortlog -n`

- View a summary of all the commits made, grouped by the committer identities (name and email):

`git shortlog -c`

- View a summary of the last 5 commits (i.e. specify a revision range):

`git shortlog HEAD~{{5}}..HEAD`

- View all users, emails and the number of commits in the current branch:

`git shortlog -sne`

- View all users, emails and the number of commits in all branches:

`git shortlog -sne --all`

