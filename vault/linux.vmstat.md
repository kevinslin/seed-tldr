---
id: linux.vmstat
title: Vmstat
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vmstat

> Report information about processes, memory, paging, block IO, traps, disks and CPU activity.
> More information: <https://linux.die.net/man/8/vmstat>.

- Display virtual memory statistics:

`vmstat`

- Display reports every 2 seconds for 5 times:

`vmstat {{2}} {{5}}`

