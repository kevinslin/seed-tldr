---
id: common.fping
title: Fping
desc: ''
updated: 1615655543055
created: 1615655543055
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fping

> A more powerful ping which can ping multiple hosts.
> More information: <https://fping.org>.

- List alive hosts within a subnet generated from a netmask:

`fping -a -g 192.168.1.0/24`

- List alive hosts within a subnet generated from an IP range:

`fping -a -g 192.168.1.1 192.168.1.254`

- List unreachable hosts within a subnet generated from a netmask:

`fping -u -g 192.168.1.0/24`

