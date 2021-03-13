---
id: common.git-replace
title: Git Replace
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git replace

> Create, list, and delete refs to replace objects.
> More information: <https://git-scm.com/docs/git-replace>.

- Replace any commit with a different one, leaving other commits unchanged:

`git replace {{object}} {{replacement}}`

- Delete existing replace refs for the given objects:

`git replace --delete {{object}}`

- Edit an object’s content interactively:

`git replace --edit {{object}}`

