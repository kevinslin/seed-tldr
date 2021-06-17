---
id: linux.mkfs-ext4
title: Mkfs Ext4
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
# mkfs.ext4

> Creates an ext4 filesystem inside a partition.

- Create an ext4 filesystem inside partition 1 on device b (`sdb1`):

`sudo mkfs.ext4 {{/dev/sdb1}}`

- Create an ext4 filesystem with a volume-label:

`sudo mkfs.ext4 -L {{volume_label}} {{/dev/sdb1}}`

