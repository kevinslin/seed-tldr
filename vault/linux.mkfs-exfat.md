---
id: linux.mkfs-exfat
title: Mkfs Exfat
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
# mkfs.exfat

> Creates an exfat filesystem inside a partition.
> More information: <https://manned.org/mkfs.exfat>.

- Create an exfat filesystem inside partition 1 on device b (`sdb1`):

`mkfs.exfat {{/dev/sdb1}}`

- Create filesystem with a volume-name:

`mkfs.exfat -n {{volume_name}} {{/dev/sdb1}}`

- Create filesystem with a volume-id:

`mkfs.exfat -i {{volume_id}} {{/dev/sdb1}}`

