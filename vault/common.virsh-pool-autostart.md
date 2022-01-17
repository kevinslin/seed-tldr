---
id: common.virsh-pool-autostart
title: Virsh Pool Autostart
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
# virsh pool-autostart

> Enable or disable autostart for a virtual machine storage pool.
> See also: `virsh`.
> More information: <https://manned.org/virsh>.

- Enable autostart for the storage pool specified by name or UUID (determine using `virsh pool-list`):

`virsh pool-autostart --pool {{name|uuid}}`

- Disable autostart for the storage pool specified by name or UUID:

`virsh pool-autostart --pool {{name|uuid}} --disable`

