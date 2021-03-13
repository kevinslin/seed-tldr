---
id: common.autojump
title: Autojump
desc: ''
updated: 1615655543044
created: 1615655543044
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# autojump

> Quickly jump among the directories you visit the most.
> Aliases like j or jc are provided for even less typing.
> More information: <https://github.com/wting/autojump>.

- Jump to a directory that contains the given pattern:

`j {{pattern}}`

- Jump to a sub-directory (child) of the current directory that contains the given pattern:

`jc {{pattern}}`

- Open a directory that contains the given pattern in the operating system file manager:

`jo {{pattern}}`

- Remove non-existing directories from the autojump database:

`j --purge`

- Show the entries in the autojump database:

`j -s`

