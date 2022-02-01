---
id: common.virsh-pool-undefine
title: Virsh Pool Undefine
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
# virsh pool-undefine

> Delete the configuration file in `/etc/libvirt/storage` for a stopped virtual machine storage pool.
> See also: `virsh`, `virsh-pool-destroy`.
> More information: <https://manned.org/virsh>.

- Delete the configuration for the storage pool specified name or UUID (determine using `virsh pool-list`):

`virsh pool-undefine --pool {{name|uuid}}`

