---
id: linux.ip-link
title: Ip Link
desc: ''
updated: 1642441815099
created: 1642441815099
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ip link

> Manage network interfaces.
> More information: <https://man7.org/linux/man-pages/man8/ip-link.8.html>.

- Show information about all network interfaces:

`ip link`

- Show information about a specific network interface:

`ip link show {{ethN}}`

- Bring a network interface up or down:

`ip link set {{ethN}} {{up|down}}`

- Give a meaningful name to a network interface:

`ip link set {{ethN}} alias "{{LAN Interface}}"`

- Change the MAC address of a network interface:

`ip link set {{ethN}} address {{ff:ff:ff:ff:ff:ff}}`

- Change the MTU size for a network interface to use jumbo frames:

`ip link set {{ethN}} mtu {{9000}}`

