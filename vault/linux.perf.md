---
id: linux.perf
title: Perf
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# perf

> Framework for Linux performance counter measurements.
> More information: <https://perf.wiki.kernel.org>.

- Display basic performance counter stats for a command:

`perf stat {{gcc hello.c}}`

- Display system-wide real-time performance counter profile:

`sudo perf top`

- Run a command and record its profile into `perf.data`:

`sudo perf record {{command}}`

- Record the profile of an existing process into `perf.data`:

`sudo perf record -p {{pid}}`

- Read `perf.data` (created by `perf record`) and display the profile:

`sudo perf report`

