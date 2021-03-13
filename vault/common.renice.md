---
id: common.renice
title: Renice
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# renice

> Alters the scheduling priority/nicenesses of one or more running processes.
> Niceness values range from -20 (most favorable to the process) to 19 (least favorable to the process).

- Change priority of a running process:

`renice -n {{niceness_value}} -p {{pid}}`

- Change priority of all processes owned by a user:

`renice -n {{niceness_value}} -u {{user}}`

- Change priority of all processes that belong to a process group:

`renice -n {{niceness_value}} --pgrp {{process_group}}`

