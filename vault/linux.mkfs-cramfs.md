---
id: linux.mkfs-cramfs
title: Mkfs Cramfs
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfs.cramfs

> Creates a ROM filesystem inside a partition.
> More information: <https://manned.org/mkfs.cramfs>.

- Create a ROM filesystem inside partition 1 on device b (`sdb1`):

`mkfs.cramfs {{/dev/sdb1}}`

- Create a ROM filesystem with a volume-name:

`mkfs.cramfs -n {{volume_name}} {{/dev/sdb1}}`

