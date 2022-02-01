---
id: common.virsh-pool-build
title: Virsh Pool Build
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
# virsh pool-build

> Build the underlying storage system for a virtual machine storage pool as defined in it's configuration file in `/etc/libvirt/storage`.
> See also: `virsh`, `virsh-pool-define-as`, `virsh-pool-start`.
> More information: <https://manned.org/virsh>.

- Build the storage pool specified by name or UUID (determine using `virsh pool-list`):

`virsh pool-build --pool {{name|uuid}}`

