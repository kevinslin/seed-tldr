---
id: linux.vgchange
title: Vgchange
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vgchange

> Change the attributes of a Logical Volume Manager (LVM) volume group.
> See also: `lvm`.
> More information: <https://manned.org/vgchange>.

- Change the activation status of logical volumes in all volume groups:

`sudo vgchange --activate {{y|n}}`

- Change the activation status of logical volumes in the specified volume group (determine with `vgscan`):

`sudo vgchange --activate {{y|n}} {{volume_group}}}`

