---
id: common.mr
title: Mr
desc: ''
updated: 1615655543072
created: 1615655543072
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mr

> Myrepos manages all your version control repositories at once.
> More information: <https://myrepos.branchable.com>.

- Register a repository:

`mr register`

- Update repositories in 5 concurrent jobs:

`mr -j{{5}} update`

- Print the status of all repositories:

`mr status`

- Checkout all repositories to the latest version:

`mr checkout`

