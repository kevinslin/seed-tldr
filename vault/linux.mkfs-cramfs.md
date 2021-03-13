---
id: linux.mkfs-cramfs
title: Mkfs Cramfs
desc: ''
updated: 1615663978750
created: 1615663978750
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfs.cramfs

> Creates a ROM filesystem inside a partition.

- Create a ROM filesystem inside partition 1 on device b (`sdb1`):

`mkfs.cramfs {{/dev/sdb1}}`

- Create a ROM filesystem with a volume-name:

`mkfs.cramfs -n {{volume_name}} {{/dev/sdb1}}`

