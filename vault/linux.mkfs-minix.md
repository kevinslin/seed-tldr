---
id: linux.mkfs-minix
title: Mkfs Minix
desc: ''
updated: 1642441815104
created: 1642441815104
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfs.minix

> Creates a Minix filesystem inside a partition.
> More information: <https://manned.org/mkfs.minix>.

- Create a Minix filesystem inside partition 1 on device b (`sdb1`):

`mkfs.minix {{/dev/sdb1}}`

