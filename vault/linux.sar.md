---
id: linux.sar
title: Sar
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sar

> Monitor performance of various Linux subsystems.

- Report I/O and transfer rate issued to physical devices, one per second (press CTRL+C to quit):

`sar -b {{1}}`

- Report a total of 10 network device statistics, one per 2 seconds:

`sar -n DEV {{2}} {{10}}`

- Report CPU utilization, one per 2 seconds:

`sar -u ALL {{2}}`

- Report a total of 20 memory utilization statistics, one per second:

`sar -r ALL {{1}} {{20}}`

- Report the run queue length and load averages, one per second:

`sar -q {{1}}`

- Report paging statistics, one per 5 seconds:

`sar -B {{5}}`

