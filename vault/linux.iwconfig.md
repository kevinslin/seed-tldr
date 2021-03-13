---
id: linux.iwconfig
title: Iwconfig
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iwconfig

> Configure and show the parameters of a wireless network interface.
> More information: <https://linux.die.net/man/8/iwconfig>.

- Show the parameters and statistics of all the interfaces:

`iwconfig`

- Show the parameters and statistics of the specified interface:

`iwconfig {{interface}}`

- Set the ESSID (network name) of the specified interface (e.g., eth0 or wlp2s0):

`iwconfig {{interface}} {{new_network_name}}`

- Set the operating mode of the specified interface:

`iwconfig {{interface}} mode {{ad hoc|Managed|Master|Repeater|Secondary|Monitor|Auto}}`
