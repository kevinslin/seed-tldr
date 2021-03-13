---
id: common.git-gc
title: Git Gc
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git gc

> Optimise the local repository by cleaning unnecessary files.
> More information: <https://git-scm.com/docs/git-gc>.

- Optimise the repository:

`git gc`

- Aggressively optimise, takes more time:

`git gc --aggressive`

- Do not prune loose objects (prunes by default):

`git gc --no-prune`

- Suppress all output:

`git gc --quiet`

- View full usage:

`git gc --help`

