---
id: common.ipsumdump
title: Ipsumdump
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipsumdump

> Summarise TCP/IP dumps into a human and machine readable ASCII format.
> More information: <https://manned.org/ipsumdump>.

- Print the source and destination IP addresses of all packets in a pcap file:

`ipsumdump --src --dst {{path/to/file.pcap}}`

- Print the timestamps, source address, source port, destination address, destination port and protocol of all packets read from a given network interface:

`ipsumdump --interface {{eth0}} -tsSdDp`

- Print the anonymised source address, anonymised destination address, and IP packet length of all packets in a pcap file:

`ipsumdump --src --dst --length --anonymize {{path/to/file.pcap}}`

