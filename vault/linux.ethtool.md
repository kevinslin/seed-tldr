---
id: linux.ethtool
title: Ethtool
desc: ''
updated: 1623965306221
created: 1623965306221
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ethtool

> Display and modify Network Interface Controller (NIC) parameters.
> More information: <http://man7.org/linux/man-pages/man8/ethtool.8.html>.

- Display the current settings for an interface:

`ethtool {{eth0}}`

- Display the driver information for an interface:

`ethtool --driver {{eth0}}`

- Display the network usage statistics for an interface:

`ethtool --statistics {{eth0}}`

- Blink one or more LEDs on an interface for 10 seconds:

`ethtool --identify {{eth0}} {{10}}`

- Set the link speed, duplex mode, and parameter auto-negotiation for a given interface:

`ethtool -s {{eth0}} speed {{10|100|1000}} duplex {{half|full}} autoneg {{on|off}}`

