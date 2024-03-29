---
id: common.ipaggcreate
title: Ipaggcreate
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
# ipaggcreate

> Produce aggregate statistics of TCP/IP dumps.
> More information: <https://manned.org/ipaggcreate>.

- Count the number of packets sent from each source address appearing in a pcap file:

`ipaggcreate --src {{path/to/file.pcap}}`

- Group and count packets read from a network interface by IP packet length:

`ipaggcreate --interface {{eth0}} --length`

- Count the number of bytes sent between each address pair appearing in a pcap file:

`ipaggcreate --address-pairs --bytes {{path/to/file.pcap}}`

