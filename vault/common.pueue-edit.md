---
id: common.pueue-edit
title: Pueue Edit
desc: ''
updated: 1623965306206
created: 1623965306206
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pueue edit

> Edit the command or path of a stashed or queued task.
> More information: <https://github.com/Nukesor/pueue>.

- Edit a task, see `pueue status` to get the task ID:

`pueue edit {{task_id}}`

- Edit the path from which a task is executed:

`pueue edit {{task_id}} --path`

- Edit a command with the specified editor:

`EDITOR={{nano}} pueue edit {{task_id}}`

