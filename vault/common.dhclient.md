---
id: common.dhclient
title: Dhclient
desc: ''
updated: 1615663978705
created: 1615663978705
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dhclient

> DHCP client.

- Get an IP address for the `eth0` interface:

`sudo dhclient {{eth0}}`

- Release an IP address for the `eth0` interface:

`sudo dhclient -r {{eth0}}`

