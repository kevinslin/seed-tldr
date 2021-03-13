---
id: common.berks
title: Berks
desc: ''
updated: 1615655543046
created: 1615655543046
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# berks

> Chef cookbook dependency manager.
> More information: <https://docs.chef.io/berkshelf.html>.

- Install cookbook dependencies into a local repo:

`berks install`

- Update a specific cookbook and its dependencies:

`berks update {{cookbook}}`

- Upload a cookbook to the Chef server:

`berks upload {{cookbook}}`

- View the dependencies of a cookbook:

`berks contingent {{cookbook}}`

