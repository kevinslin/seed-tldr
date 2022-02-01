---
id: linux.vmstat
title: Vmstat
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vmstat

> Report information about processes, memory, paging, block IO, traps, disks and CPU activity.
> More information: <https://manned.org/vmstat>.

- Display virtual memory statistics:

`vmstat`

- Display reports every 2 seconds for 5 times:

`vmstat {{2}} {{5}}`

