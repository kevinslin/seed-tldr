---
id: common.airmon-ng
title: Airmon Ng
desc: ''
updated: 1623965306172
created: 1623965306172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airmon-ng

> Activate monitor mode on wireless network devices.
> More information: <https://www.aircrack-ng.org/doku.php?id=airmon-ng>.

- List wireless devices and their statuses:

`sudo airmon-ng`

- Turn on monitor mode for a specific device:

`sudo airmon-ng start {{wlan0}}`

- Kill disturbing processes that use wireless devices:

`sudo airmon-ng check kill`

- Turn off monitor mode for a specific network interface:

`sudo airmon-ng stop {{wlan0mon}}`

