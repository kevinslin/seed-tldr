---
id: linux.lscpu
title: Lscpu
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lscpu

> Displays information about the CPU architecture.
> More information: <https://manned.org/lscpu>.

- Display information about all CPUs:

`lscpu`

- Display information in a table:

`lscpu --extended`

- Display only information about offline CPUs in a table:

`lscpu --extended --offline`

