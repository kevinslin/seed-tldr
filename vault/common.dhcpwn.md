---
id: common.dhcpwn
title: Dhcpwn
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
# dhcpwn

> Test DHCP IP exhaustion attacks and sniff local DHCP traffic.
> More information: <https://github.com/mschwager/dhcpwn>.

- Flood the network with IP requests:

`dhcpwn --interface {{network_interface}} flood --count {{number_of_requests}}`

- Sniff local DHCP traffic:

`dhcpwn --interface {{network_interface}} sniff`

