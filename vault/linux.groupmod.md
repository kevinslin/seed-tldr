---
id: linux.groupmod
title: Groupmod
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# groupmod

> Modify existing user groups in the system.

- Change the group name:

`groupmod -n {{new_group_name}} {{old_group_name}}`

- Change the group id:

`groupmod -g {{new_group_id}} {{old_group_name}}`

