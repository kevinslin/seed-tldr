---
id: linux.mkfs
title: Mkfs
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

