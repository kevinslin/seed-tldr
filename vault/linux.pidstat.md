---
id: linux.pidstat
title: Pidstat
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pidstat

> Show system resource usage, including CPU, memory, IO etc.

- Show CPU statistics at a 2 second interval for 10 times:

`pidstat {{2}} {{10}}`

- Show page faults and memory utilization:

`pidstat -r`

- Show input/output usage per process id:

`pidstat -d`

- Show information on a specific PID:

`pidstat -p {{PID}}`

- Show memory statistics for all processes whose command name include "fox" or "bird":

`pidstat -C "{{fox|bird}}" -r -p ALL`

