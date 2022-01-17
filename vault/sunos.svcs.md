---
id: sunos.svcs
title: Svcs
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# svcs

> List information about running services.
> More information: <https://www.unix.com/man-page/linux/1/svcs>.

- List all running services:

`svcs`

- List services that are not running:

`svcs -vx`

- List information about a service:

`svcs apache`

- Show location of service log file:

`svcs -L apache`

- Display end of a service log file:

`tail $(svcs -L apache)`

