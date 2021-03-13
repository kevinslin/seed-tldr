---
id: linux.foreman
title: Foreman
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# foreman

> Manage Procfile-based applications.

- Start an application with the Procfile in the current directory:

`foreman start`

- Start an application with a specified Procfile:

`foreman start -f {{Procfile}}`

- Start a specific application:

`foreman start {{process}}`

- Validate Procfile format:

`foreman check`

- Run one-off commands with the process's environment:

`foreman run {{command}}`

- Start all processes except the one named "worker":

`foreman start -m all=1,{{worker}}=0`

