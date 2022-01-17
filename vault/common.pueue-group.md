---
id: common.pueue-group
title: Pueue Group
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
# pueue group

> Display, add or remove groups.
> More information: <https://github.com/Nukesor/pueue>.

- Show all groups with their statuses and number of parallel jobs:

`pueue group`

- Add a custom group:

`pueue group --add "{{group_name}}"`

- Remove a group and move its tasks to the default group:

`pueue group --remove "{{group_name}}"`

