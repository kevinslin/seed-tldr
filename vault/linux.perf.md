---
id: linux.perf
title: Perf
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

