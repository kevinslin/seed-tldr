---
id: common.virsh-pool-info
title: Virsh Pool Info
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
# virsh pool-info

> List information about a virtual machine storage pool.
> See also: `virsh`.
> More information: <https://manned.org/virsh>.

- List the name, UUID, state, persistence type, autostart status, capacity, space allocated, and space available for the storage pool specified by name or UUID (determine using `virsh pool-list`):

`virsh pool-info --pool {{name|uuid}}`

