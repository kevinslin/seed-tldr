---
id: common.virsh-pool-list
title: Virsh Pool List
desc: ''
updated: 1642441815080
created: 1642441815080
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virsh pool-list

> List information about virtual machine storage pools.
> See also: `virsh`, `virsh-pool-autostart`, `virsh-pool-define-as`.
> More information: <https://manned.org/virsh>.

- List the name, state, and whether autostart is enabled or disabled for active storage pools:

`virsh pool-list`

- List information for active and inactive or just inactive storage pools:

`virsh pool-list --{{all|inactive}}`

- List extended information about persistence, capacity, allocation, and available space for active storage pools:

`virsh pool-list --details`

- List information for active storage pools with either autostart enabled or disabled:

`virsh pool-list --{{autostart|no-autostart}}`

- List information for active storage pools that are either persistent or transient:

`virsh pool-list --{{persistent|transient}}`

- List the name and UUID of active storage pools:

`virsh pool-list --name --uuid`

