---
id: linux.perf
title: Perf
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
# perf

> Framework for linux performance counter measurements.

- Display basic performance counter stats for a command:

`perf stat {{gcc hello.c}}`

- Display system-wide real time performance counter profile:

`sudo perf top`

- Run a command and record its profile into `perf.data`:

`sudo perf record {{command}}`

- Read `perf.data` (created by `perf record`) and display the profile:

`sudo perf report`

