---
id: common.dhclient
title: Dhclient
desc: ''
updated: 1623965016119
created: 1623965016119
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dhclient

> DHCP client.
> More information: <https://manned.org/dhclient>.

- Get an IP address for the `eth0` interface:

`sudo dhclient {{eth0}}`

- Release an IP address for the `eth0` interface:

`sudo dhclient -r {{eth0}}`

