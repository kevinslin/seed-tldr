---
id: common.ionice
title: Ionice
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ionice

> Get or set program I/O scheduling class and priority.
> Scheduling classes: 1 (realtime), 2 (best-effort), 3 (idle).
> Priority levels: 0 (the highest) - 7 (the lowest).

- Set I/O scheduling class of a running process:

`ionice -c {{scheduling_class}} -p {{pid}}`

- Run a command with custom I/O scheduling class and priority:

`ionice -c {{scheduling_class}} -n {{priority}} {{command}}`

- Print the I/O scheduling class and priority of a running process:

`ionice -p {{pid}}`

