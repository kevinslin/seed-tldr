---
id: linux.vgcreate
title: Vgcreate
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
# vgcreate

> Create volume groups combining multiple mass-storage devices.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/vgcreate.8.html>.

- Create a new volume group called vg1 using the `/dev/sda1` device:

`vgcreate {{vg1}} {{/dev/sda1}}`

- Create a new volume group called vg1 using multiple devices:

`vgcreate {{vg1}} {{/dev/sda1}} {{/dev/sdb1}} {{/dev/sdc1}}`

