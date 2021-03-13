---
id: linux.pidof
title: Pidof
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pidof

> Gets the ID of a process using its name.

- List all process IDs with given name:

`pidof {{bash}}`

- List a single process ID with given name:

`pidof -s {{bash}}`

- List process IDs including scripts with given name:

`pidof -x {{script.py}}`

- Kill all processes with given name:

`kill "$(pidof {{name}})" `

