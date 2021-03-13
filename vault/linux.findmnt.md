---
id: linux.findmnt
title: Findmnt
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

