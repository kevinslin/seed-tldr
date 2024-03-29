---
id: common.ps
title: Ps
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ps

> Information about running processes.
> More information: <https://manned.org/ps>.

- List all running processes:

`ps aux`

- List all running processes including the full command string:

`ps auxww`

- Search for a process that matches a string:

`ps aux | grep {{string}}`

- List all processes of the current user in extra full format:

`ps --user $(id -u) -F`

- List all processes of the current user as a tree:

`ps --user $(id -u) f`

- Get the parent PID of a process:

`ps -o ppid= -p {{pid}}`

- Sort processes by memory consumption:

`ps --sort size`

