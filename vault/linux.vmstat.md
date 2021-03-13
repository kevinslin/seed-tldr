---
id: linux.vmstat
title: Vmstat
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# vmstat

> Report information about processes, memory, paging, block IO, traps, disks and CPU activity.
> More information: <https://linux.die.net/man/8/vmstat>.

- Display virtual memory statistics:

`vmstat`

- Display reports every 2 seconds for 5 times:

`vmstat {{2}} {{5}}`

