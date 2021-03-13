---
id: linux.mkfs
title: Mkfs
desc: ''
updated: 1615663978750
created: 1615663978750
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfs

> Build a Linux filesystem on a hard disk partition.
> This command is deprecated in favor of filesystem specific mkfs.<type> utils.

- Build a Linux ext2 filesystem on a partition:

`mkfs {{path/to/partition}}`

- Build a filesystem of a specified type:

`mkfs -t {{ext4}} {{path/to/partition}}`

- Build a filesystem of a specified type and check for bad blocks:

`mkfs -c -t {{ntfs}} {{path/to/partition}}`

