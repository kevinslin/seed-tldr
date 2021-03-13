---
id: linux.apport-bug
title: Apport Bug
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# apport-bug

> File a bug report on Ubuntu.
> More information: <https://wiki.ubuntu.com/Apport>.

- Report a bug about the whole system:

`apport-bug`

- Report a bug about a specific package:

`apport-bug {{package}}`

- Report a bug about a specific executable:

`apport-bug {{path/to/executable}}`

- Report a bug about a specific process:

`apport-bug {{PID}}`

