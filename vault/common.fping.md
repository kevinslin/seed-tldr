---
id: common.fping
title: Fping
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

