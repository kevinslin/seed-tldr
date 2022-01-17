---
id: linux.mkfs-vfat
title: Mkfs Vfat
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
# mkfs.vfat

> Creates an MS-DOS filesystem inside a partition.
> More information: <https://manned.org/mkfs.vfat>.

- Create a vfat filesystem inside partition 1 on device b (`sdb1`):

`mkfs.vfat {{/dev/sdb1}}`

- Create filesystem with a volume-name:

`mkfs.vfat -n {{volume_name}} {{/dev/sdb1}}`

- Create filesystem with a volume-id:

`mkfs.vfat -i {{volume_id}} {{/dev/sdb1}}`

- Use 5 instead of 2 file allocation tables:

`mkfs.vfat -f 5 {{/dev/sdb1}}`

