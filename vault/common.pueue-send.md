---
id: common.pueue-send
title: Pueue Send
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
# pueue send

> Send input to a task.
> More information: <https://github.com/Nukesor/pueue>.

- Send input to a running command:

`pueue send {{task_id}} "{{input}}"`

- Send confirmation to a task expecting y/N (e.g. apt, cp):

`pueue send {{task_id}} {{y}}`

