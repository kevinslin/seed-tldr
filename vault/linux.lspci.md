---
id: linux.lspci
title: Lspci
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lspci

> List all PCI devices.

- Show a brief list of devices:

`lspci`

- Display additional info:

`lspci -v`

- Display drivers and modules handling each device:

`lspci -k`

- Show a specific device:

`lspci -s {{00:18.3}}`

- Dump info in a readable form:

`lspci -vm`

