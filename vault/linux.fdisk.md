---
id: linux.fdisk
title: Fdisk
desc: ''
updated: 1615663978746
created: 1615663978746
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

