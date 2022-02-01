---
id: linux.wg-quick
title: Wg Quick
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
# wg-quick

> Quickly set up WireGuard tunnels based on config files.
> More information: <https://www.wireguard.com/quickstart/>.

- Set up a VPN tunnel:

`wg-quick up {{interface_name}}`

- Delete a VPN tunnel:

`wg-quick down {{interface_name}}`

