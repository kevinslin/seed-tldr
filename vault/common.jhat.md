---
id: common.jhat
title: Jhat
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# jhat

> Java Heap Analysis Tool.

- Analyze a heap dump (from jmap), view via http on port 7000:

`jhat {{dump_file.bin}}`

- Analyze a heap dump, specifying an alternate port for the http server:

`jhat -p {{port}} {{dump_file.bin}}`

- Analyze a dump letting jhat use up to 8GB RAM (2-4x dump size recommended):

`jhat -J-mx8G {{dump_file.bin}}`

