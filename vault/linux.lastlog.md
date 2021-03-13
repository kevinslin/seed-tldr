---
id: linux.lastlog
title: Lastlog
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lastlog

> Show the most recent login of all users or of a given user.

- Display the most recent login of all users:

`lastlog`

- Display lastlog record of the specified user:

`lastlog -u {{username}}`

- Display records before than 7 days:

`lastlog -b {{7}}`

- Display records more recent than 3 days:

`lastlog -t {{3}}`

