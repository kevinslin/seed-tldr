---
id: linux.ip-address
title: Ip Address
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
# ip address

> IP Address management subcommand.
> More information: <https://manned.org/ip-address>.

- List network interfaces and their associated IP addresses:

`ip address`

- Filter to show only active network interfaces:

`ip address show up`

- Display information about a specific network interface:

`ip address show dev {{eth0}}`

- Add an IP address to a network interface:

`ip address add {{ip_address}} dev {{eth0}}`

- Remove an IP address from a network interface:

`ip address delete {{ip_address}} dev {{eth0}}`

- Delete all IP addresses in a given scope from a network interface:

`ip address flush dev {{eth0}} scope {{global|host|link}}`

