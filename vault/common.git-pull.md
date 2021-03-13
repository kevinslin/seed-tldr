---
id: common.git-pull
title: Git Pull
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git pull

> Fetch branch from a remote repository and merge it to local repository.
> More information: <https://git-scm.com/docs/git-pull>.

- Download changes from default remote repository and merge it:

`git pull`

- Download changes from default remote repository and use fast forward:

`git pull --rebase`

- Download changes from given remote repository and branch, then merge them into HEAD:

`git pull {{remote_name}} {{branch}}`

