---
id: linux.wol
title: Wol
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wol

> Client for sending Wake-on-LAN magic packets.
> More information: <https://sourceforge.net/projects/wake-on-lan/>.

- Send a WoL packet to a device:

`wol {{mac_address}}`

- Send a WoL packet to a device in another subnet based on its IP:

`wol --ipaddr={{ip_address}} {{mac_address}}`

- Send a WoL packet to a device in another subnet based on its hostname:

`wol --host={{hostname}} {{mac_address}}`

- Send a WoL packet to a specific port on a host:

`wol --port={{port_number}} {{mac_address}}`

- Read hardware addresses, IP addresses/hostnames, optional ports and SecureON passwords from a file:

`wol --file={{path/to/file}}`

- Turn on verbose output:

`wol --verbose {{mac_address}}`

