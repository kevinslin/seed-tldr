---
id: linux.mpstat
title: Mpstat
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mpstat

> Report CPU statistics.

- Display CPU statistics every 2 seconds:

`mpstat {{2}}`

- Display 5 reports, one by one, at 2 second intervals:

`mpstat {{2}} {{5}}`

- Display 5 reports, one by one, from a given processor, at 2 second intervals:

`mpstat -P {{0}} {{2}} {{5}}`

