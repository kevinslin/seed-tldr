---
id: common.arp
title: Arp
desc: ''
updated: 1615655543044
created: 1615655543044
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

