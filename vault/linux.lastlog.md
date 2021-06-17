---
id: linux.lastlog
title: Lastlog
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lastlog

> Show the most recent login of all users or of a given user.

- Display the most recent login of all users:

`lastlog`

- Display lastlog record of the specified user:

`lastlog -u {{username}}`

- Display records before than 7 days:

`lastlog -b {{7}}`

- Display records more recent than 3 days:

`lastlog -t {{3}}`

