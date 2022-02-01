---
id: linux.prlimit
title: Prlimit
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prlimit

> Get or set process resource soft and hard limits.
> Given a process ID and one or more resources, prlimit tries to retrieve and/or modify the limits.
> More information: <https://manned.org/prlimit>.

- Display limit values for all current resources for the running parent process:

`prlimit`

- Display limit values for all current resources of a specified process:

`prlimit --pid {{pid number}}`

- Run a command with a custom number of open files limit:

`prlimit --nofile={{10}} {{command}}`

