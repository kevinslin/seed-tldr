---
id: common.virsh-pool-destroy
title: Virsh Pool Destroy
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
# virsh pool-destroy

> Stop an active virtual machine storage pool.
> See also: `virsh`, `virsh-pool-delete`.
> More information: <https://manned.org/virsh>.

- Stop a storage pool specified by name or UUID (determine using `virsh pool-list`):

`virsh pool-destroy --pool {{name|uuid}}`

