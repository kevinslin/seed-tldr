---
id: linux.squeue
title: Squeue
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# squeue

> View the jobs queued in the SLURM scheduler.

- View the queue:

`squeue`

- View jobs queued by a specific user:

`squeue -u {{username}}`

- View the queue and refresh every 5 seconds:

`squeue -i {{5}}`

- View the queue with expected start times:

`squeue --start`

