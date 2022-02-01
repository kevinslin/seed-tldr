---
id: linux.lastlog
title: Lastlog
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lastlog

> Show the most recent login of all users or of a given user.
> More information: <https://manned.org/lastlog>.

- Display the most recent login of all users:

`lastlog`

- Display the lastlog record of the specified user:

`lastlog --user {{username}}`

- Display records older than 7 days:

`lastlog --before {{7}}`

- Display records more recent than 3 days:

`lastlog -time {{3}}`

