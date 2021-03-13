---
id: linux.useradd
title: Useradd
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# useradd

> Create a new user.

- Create new user:

`useradd {{name}}`

- Create new user with a default home directory:

`useradd --create-home {{name}}`

- Create new user with specified shell:

`useradd --shell {{path/to/shell}} {{name}}`

- Create new user belonging to additional groups (mind the lack of whitespace):

`useradd --groups {{group1,group2}} {{name}}`

- Create new system user without a home directory:

`useradd --no-create-home --system {{name}}`

