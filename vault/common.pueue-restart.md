---
id: common.pueue-restart
title: Pueue Restart
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
# pueue restart

> Restart tasks.
> More information: <https://github.com/Nukesor/pueue>.

- Restart a specific task:

`pueue restart {{task_id}}`

- Restart multiple tasks at once, and start them immediately (do not enqueue):

`pueue restart --start-immediately {{task_id}} {{task_id}}`

- Restart a specific task from a different path:

`pueue restart --edit-path {{task_id}}`

- Edit a command before restarting:

`pueue restart --edit {{task_id}}`

- Restart a task in-place (without enqueuing as a separate task):

`pueue restart --in-place {{task_id}}`

- Restart all failed tasks and stash them:

`pueue restart --all-failed --stashed`

