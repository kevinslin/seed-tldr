---
id: linux.iostat
title: Iostat
desc: ''
updated: 1623965306223
created: 1623965306223
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iostat

> Report statistics for devices and partitions.

- Display a report of CPU and disk statistics since system startup:

`iostat`

- Display a report of CPU and disk statistics with units converted to megabytes:

`iostat -m`

- Display CPU statistics:

`iostat -c`

- Display disk statistics with disk names (including LVM):

`iostat -N`

- Display extended disk statistics with disk names for device "sda":

`iostat -xN {{sda}}`

- Display incremental reports of CPU and disk statistics every 2 seconds:

`iostat {{2}}`

