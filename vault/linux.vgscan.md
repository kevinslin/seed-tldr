---
id: linux.vgscan
title: Vgscan
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
# vgscan

> Scan for volume groups on all supported Logical Volume Manager (LVM) block devices.
> See also `lvm`, `vgchange`.
> More information: <https://manned.org/vgscan>.

- Scan for volume groups and print information about each group found:

`sudo vgscan`

- Scan for volume groups and add the special files in `/dev`, if they don't already exist, needed to access the logical volumes in the found groups :

`sudo vgscan --mknodes`

