---
id: osx.top
title: Top
desc: ''
updated: 1615663978761
created: 1615663978761
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# top

> Display dynamic real-time information about running processes.

- Start top, all options are available in the interface:

`top`

- Start top sorting processes by internal memory size (default order - process ID):

`top -o mem`

- Start top sorting processes first by CPU, then by running time:

`top -o cpu -O time`

- Start top displaying only processes owned by given user:

`top -user {{user_name}}`

- Get help about interactive commands:

`?`
