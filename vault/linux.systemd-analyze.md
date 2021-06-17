---
id: linux.systemd-analyze
title: Systemd Analyze
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
# systemd-analyze

> Show timing details about the boot process of units (services, mount points, devices, sockets).

- List time of each unit to start up:

`systemd-analyze blame`

- Print a tree of the time critical chain of units:

`systemd-analyze critical-chain`

- Create an SVG file showing when each system service started, highlighting the time that they spent on initialization:

`systemd-analyze plot > {{path/to/file.svg}}`

- Plot a dependency graph and convert it to an SVG file:

`systemd-analyze dot | dot -T{{svg}} > {{path/to/file.svg}}`

