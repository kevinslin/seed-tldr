---
id: common.pueue-log
title: Pueue Log
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
# pueue log

> Display the log output of 1 or more tasks.
> See also: `pueue status`.
> More information: <https://github.com/Nukesor/pueue>.

- Show the last few lines of output from all tasks:

`pueue log`

- Show the full output of a task:

`pueue log {{task_id}}`

- Show the last few lines of output from several tasks:

`pueue log {{task_id}} {{task_id}}`

- Print a specific number of lines from the tail of output:

`pueue log --lines {{number_of_lines}} {{task_id}}`

