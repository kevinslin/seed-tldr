---
id: linux.mkfs-ntfs
title: Mkfs Ntfs
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
# mkfs.ntfs

> Creates a NTFS filesystem inside a partition.

- Create a NTFS filesystem inside partition 1 on device b (`sdb1`):

`mkfs.ntfs {{/dev/sdb1}}`

- Create filesystem with a volume-label:

`mkfs.ntfs -L {{volume_label}} {{/dev/sdb1}}`

- Create filesystem with specific UUID:

`mkfs.ntfs -U {{UUID}} {{/dev/sdb1}}`

