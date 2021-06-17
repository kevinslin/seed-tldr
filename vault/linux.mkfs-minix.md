---
id: linux.mkfs-minix
title: Mkfs Minix
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfs.minix

> Creates a Minix filesystem inside a partition.

- Create a Minix filesystem inside partition 1 on device b (`sdb1`):

`mkfs.minix {{/dev/sdb1}}`

