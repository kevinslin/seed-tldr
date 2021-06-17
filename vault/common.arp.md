---
id: common.arp
title: Arp
desc: ''
updated: 1623965016112
created: 1623965016112
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arp

> Show and manipulate your system's ARP cache.
> More information: <https://manned.org/arp>.

- Show the current ARP table:

`arp -a`

- Clear the entire cache:

`sudo arp -a -d`

- Delete a specific entry:

`arp -d {{address}}`

- Create an entry in the ARP table:

`arp -s {{address}} {{mac_address}}`

