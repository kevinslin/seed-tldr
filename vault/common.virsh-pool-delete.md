---
id: common.virsh-pool-delete
title: Virsh Pool Delete
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
# virsh pool-delete

> Delete the underlying storage system of an inactive virtual machine storage pool.
> See also: `virsh`, `virsh-pool-destroy`, `virsh-pool-undefine`.
> More information: <https://manned.org/virsh>.

- Delete the underlying storage system for the storage pool specified by name or UUID (determine using `virsh pool-list`):

`virsh pool-delete --pool {{name|uuid}}`

