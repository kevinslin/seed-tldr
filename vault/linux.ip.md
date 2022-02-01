---
id: linux.ip
title: Ip
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
# ip

> Show / manipulate routing, devices, policy routing and tunnels.
> Some subcommands such as `ip address` have their own usage documentation.
> More information: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- List interfaces with detailed info:

`ip address`

- List interfaces with brief network layer info:

`ip -brief address`

- List interfaces with brief link layer info:

`ip -brief link`

- Display the routing table:

`ip route`

- Show neighbors (ARP table):

`ip neighbour`

- Make an interface up/down:

`ip link set {{interface}} up/down`

- Add/Delete an IP address to an interface:

`ip addr add/del {{ip}}/{{mask}} dev {{interface}}`

- Add a default route:

`ip route add default via {{ip}} dev {{interface}}`

