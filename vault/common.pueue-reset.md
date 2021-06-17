---
id: common.pueue-reset
title: Pueue Reset
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
# pueue reset

> Kill everything and reset.
> More information: <https://github.com/Nukesor/pueue>.

- Kill all tasks and remove everything (logs, status, groups, task IDs):

`pueue reset`

- Kill all tasks, terminate their children, and reset everything:

`pueue reset --children`

- Reset without asking for confirmation:

`pueue reset --force`

