---
id: common.pueue-pause
title: Pueue Pause
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
# pueue pause

> Pause running tasks or groups.
> See also: `pueue start`.
> More information: <https://github.com/Nukesor/pueue>.

- Pause all tasks in the default group:

`pueue pause`

- Pause a running task:

`pueue pause {{task_id}}`

- Pause a running task and stop all its direct children:

`pueue pause --children {{task_id}}`

- Pause all tasks in a group and prevent it from starting new tasks:

`pueue pause --group {{group_name}}`

- Pause all tasks and prevent all groups from starting new tasks:

`pueue pause --all`

