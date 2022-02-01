---
id: common.pueue-kill
title: Pueue Kill
desc: ''
updated: 1642441815062
created: 1642441815062
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pueue kill

> Kill running tasks or whole groups.
> More information: <https://github.com/Nukesor/pueue>.

- Kill all tasks in the default group:

`pueue kill`

- Kill a specific task:

`pueue kill {{task_id}}`

- Kill a task and terminate all its child processes:

`pueue kill --children {{task_id}}`

- Kill all tasks in a group and pause the group:

`pueue kill --group {{group_name}}`

- Kill all tasks across all groups and pause all groups:

`pueue kill --all`

