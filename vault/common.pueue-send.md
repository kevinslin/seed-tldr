---
id: common.pueue-send
title: Pueue Send
desc: ''
updated: 1623965016146
created: 1623965016146
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

