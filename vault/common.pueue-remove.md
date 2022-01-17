---
id: common.pueue-remove
title: Pueue Remove
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
# pueue remove

> Remove tasks from the list. Running or paused tasks need to be killed first.
> More information: <https://github.com/Nukesor/pueue>.

- Remove a killed or finished task:

`pueue remove {{task_id}}`

- Remove multiple tasks at once:

`pueue remove {{task_id}} {{task_id}}`

