---
id: linux.cfdisk
title: Cfdisk
desc: ''
updated: 1615663978742
created: 1615663978742
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cfdisk

> A program for managing partition tables and partitions on a hard disk using a curses UI.
> More information: <https://linux.die.net/man/8/cfdisk>.

- Start the partition manipulator with a specific device:

`cfdisk {{/dev/sdX}}`

- Create a new partition table for a specific device and manage it:

`cfdisk --zero {{/dev/sdX}}`

