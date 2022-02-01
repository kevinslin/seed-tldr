---
id: common.renice
title: Renice
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# renice

> Alters the scheduling priority/nicenesses of one or more running processes.
> Niceness values range from -20 (most favorable to the process) to 19 (least favorable to the process).
> More information: <https://manned.org/renice>.

- Change priority of a running process:

`renice -n {{niceness_value}} -p {{pid}}`

- Change priority of all processes owned by a user:

`renice -n {{niceness_value}} -u {{user}}`

- Change priority of all processes that belong to a process group:

`renice -n {{niceness_value}} --pgrp {{process_group}}`

