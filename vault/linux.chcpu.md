---
id: linux.chcpu
title: Chcpu
desc: ''
updated: 1615663978742
created: 1615663978742
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chcpu

> Enable/disable a system's CPUs.

- Disable CPUs via a list of CPU ID numbers:

`chcpu -d {{1,3}}`

- Enable a set of CPUs via a range of CPU ID numbers:

`chcpu -e {{1-10}}`

