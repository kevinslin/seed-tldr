---
id: linux.fdisk
title: Fdisk
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
# fdisk

> A program for managing partition tables and partitions on a hard disk.

- List partitions:

`fdisk -l`

- Start the partition manipulator:

`fdisk {{/dev/sdX}}`

