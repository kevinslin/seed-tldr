---
id: linux.lslogins
title: Lslogins
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lslogins

> Show information about users on a Linux system.
> More information: <https://man7.org/linux/man-pages/man1/lslogins.1.html>.

- Display users in the system:

`lslogins`

- Display users belonging to a specific group:

`lslogins --groups={{groups}}`

- Display user accounts:

`lslogins --user-accs`

- Display last logins:

`lslogins --last`

- Display system accounts:

`lslogins --system-accs`

- Display supplementary groups:

`lslogins --supp-groups`

