---
id: linux.mke2fs
title: Mke2fs
desc: ''
updated: 1623965016164
created: 1623965016164
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mke2fs

> Creates a Linux filesystem inside a partition.

- Create an ext2 filesystem in partition 1 of device b (`sdb1`):

`mkfs.ext2 {{/dev/sdb1}}`

- Create an ext3 filesystem in partition 1 of device b (`sdb1`):

`mkfs.ext3 {{/dev/sdb1}}`

- Create an ext4 filesystem in partition 1 of device b (`sdb1`):

`mkfs.ext4 {{/dev/sdb1}}`

