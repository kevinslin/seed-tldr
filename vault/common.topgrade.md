---
id: common.topgrade
title: Topgrade
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# topgrade

> Update all applications on the system.
> More information: <https://github.com/r-darwish/topgrade>.

- Run updates:

`topgrade`

- Say yes to all updates:

`topgrade -y`

- Cleanup temporary/old files:

`topgrade -c`

- Disable a certain update operation:

`topgrade -disable {{operation}}`

- Only perform a certain update operation:

`topgrade --only {{operation}}`

- Edit the config file with default editor:

`topgrade --edit-config`

