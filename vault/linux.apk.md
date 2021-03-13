---
id: linux.apk
title: Apk
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# apk

> Alpine Linux package management tool.

- Update repository indexes from all remote repositories:

`apk update`

- Install a new package:

`apk add {{package}}`

- Remove a package:

`apk del {{package}}`

- Repair package or upgrade it without modifying main dependencies:

`apk fix {{package}}`

- Search package via keyword:

`apk search {{keyword}}`

- Get info about a specific package:

`apk info {{package}}`

