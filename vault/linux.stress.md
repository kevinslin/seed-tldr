---
id: linux.stress
title: Stress
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
# stress

> A tool to stress test CPU, memory, and IO on a Linux system.

- Spawn 4 workers to stress test CPU:

`stress -c {{4}}`

- Spawn 2 workers to stress test IO and timeout after 5 seconds:

`stress -i {{2}} -t {{5}}`

- Spawn 2 workers to stress test memory (each worker allocates 256M bytes):

`stress -m {{2}} --vm-bytes {{256M}}`

- Spawn 2 workers spinning on write()/unlink() (each worker writes 1G bytes):

`stress -d {{2}} --hdd-bytes {{1GB}}`

