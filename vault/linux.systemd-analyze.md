---
id: linux.systemd-analyze
title: Systemd Analyze
desc: ''
updated: 1615663978756
created: 1615663978756
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-analyze

> Show timing details about the boot process of units (services, mount points, devices, sockets).

- List time of each unit to start up:

`systemd-analyze blame`

- Print a tree of the time critical chain of units:

`systemd-analyze critical-chain`

