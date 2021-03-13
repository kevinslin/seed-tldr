---
id: linux.login
title: Login
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# login

> Initiates a session for a user.

- Login as a user:

`login {{user}}`

- Login as user without authentication if user is preauthenticated:

`login -f {{user}}`

- Login as user and preserve environment:

`login -p {{user}}`

- Login as a user on a remote host:

`login -h {{host}} {{user}}`

