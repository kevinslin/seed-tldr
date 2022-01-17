---
id: linux.mssh
title: Mssh
desc: ''
updated: 1642441815104
created: 1642441815104
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mssh

> GTK+ based SSH client for interacting with multiple SSH servers at once.
> More information: <https://manned.org/mssh>.

- Open a new window and connect to multiple SSH servers:

`mssh {{user@host1}} {{user@host2}} {{...}}`

- Open a new window and connect to a group of servers predefined in `~/.mssh_clusters`:

`mssh --alias {{alias_name}}`

