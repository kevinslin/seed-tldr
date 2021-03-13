---
id: common.git-add
title: Git Add
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git add

> Adds changed files to the index.
> More information: <https://git-scm.com/docs/git-add>.

- Add a file to the index:

`git add {{path/to/file}}`

- Add all files (tracked and untracked):

`git add -A`

- Only add already tracked files:

`git add -u`

- Also add ignored files:

`git add -f`

- Interactively stage parts of files:

`git add -p`

- Interactively stage parts of a given file:

`git add -p {{path/to/file}}`

- Interactively stage a file:

`git add -i`

