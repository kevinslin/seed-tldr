---
id: common.htop
title: Htop
desc: ''
updated: 1642441815033
created: 1642441815033
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# htop

> Display dynamic real-time information about running processes. An enhanced version of `top`.
> More information: <https://htop.dev/>.

- Start htop:

`htop`

- Start htop displaying processes owned by a specific user:

`htop --user {{username}}`

- Sort processes by a specified `sort_item` (use `htop --sort help` for available options):

`htop --sort {{sort_item}}`

- See interactive commands while running htop:

`?`

- Display help:

`htop --help`

