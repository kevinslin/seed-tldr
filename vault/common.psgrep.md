---
id: common.psgrep
title: Psgrep
desc: ''
updated: 1615655543079
created: 1615655543079
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# psgrep

> Search running processes with `grep`.
> More information: <https://jvz.github.io/psgrep>.

- Find process lines containing a specific string:

`psgrep {{process_name}}`

- Find process lines containing a specific string, excluding headers:

`psgrep -n {{process_name}}`

- Search using a simplified format (PID, user, command):

`psgrep -s {{process_name}}`

