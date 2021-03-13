---
id: linux.mkfs-fat
title: Mkfs Fat
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mkfs.fat

> Creates an MS-DOS filesystem inside a partition.

- Create a fat filesystem inside partition 1 on device b (`sdb1`):

`mkfs.fat {{/dev/sdb1}}`

- Create filesystem with a volume-name:

`mkfs.fat -n {{volume_name}} {{/dev/sdb1}}`

- Create filesystem with a volume-id:

`mkfs.fat -i {{volume_id}} {{/dev/sdb1}}`

- Use 5 instead of 2 file allocation tables:

`mkfs.fat -f 5 {{/dev/sdb1}}`

