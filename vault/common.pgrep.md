---
id: common.pgrep
title: Pgrep
desc: ''
updated: 1615655543078
created: 1615655543078
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pgrep

> Find or signal process by name.

- Return PIDs of any running processes with a matching command string:

`pgrep {{process_name}}`

- Search full command line with parameters instead of just the process name:

`pgrep -f "{{process_name}} {{parameter}}"`

- Search for process run by a specific user:

`pgrep -u root {{process_name}}`

