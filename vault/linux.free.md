---
id: linux.free
title: Free
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# free

> Display amount of free and used memory in the system.

- Display system memory:

`free`

- Display memory in Bytes/KB/MB/GB:

`free -{{b|k|m|g}}`

- Display memory in human readable units:

`free -h`

- Refresh the output every 2 seconds:

`free -s {{2}}`
