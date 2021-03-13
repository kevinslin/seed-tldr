---
id: common.arp
title: Arp
desc: ''
updated: 1615663978698
created: 1615663978698
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arp

> Show and manipulate your system's ARP cache.

- Show current arp table:

`arp -a`

- Clear the entire cache:

`sudo arp -a -d`

- Delete a specific entry:

`arp -d {{address}}`

- Create an entry:

`arp -s {{address}} {{mac_address}}`

