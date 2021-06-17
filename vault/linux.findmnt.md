---
id: linux.findmnt
title: Findmnt
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# findmnt

> Find your filesystem.

- List all mounted filesystems:

`findmnt`

- Search for a device:

`findmnt {{/dev/sdb1}}`

- Search for a mountpoint:

`findmnt {{/}}`

- Find filesystems in specific type:

`findmnt -t {{ext4}}`

- Find filesystems with specific label:

`findmnt LABEL={{BigStorage}}`

