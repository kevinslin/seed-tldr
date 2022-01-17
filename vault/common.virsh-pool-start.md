---
id: common.virsh-pool-start
title: Virsh Pool Start
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
# virsh pool-start

> Start a previously configured but inactive virtual machine storage pool.
> See also: `virsh`, `virsh-pool-define-as`, `virsh-pool-destroy`.
> More information: <https://manned.org/virsh>.

- Start the storage pool specified by name or UUID (determine using `virsh pool-list`) and create the underlying storage system if it doesn't exist:

`virsh pool-start --pool {{name|uuid}} --build`

