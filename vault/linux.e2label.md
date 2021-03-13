---
id: linux.e2label
title: E2label
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# e2label

> Change the label on an ext2/ext3/ext4 filesystem.

- Change the volume label on a specific ext partition:

`e2label {{/dev/sda1}} "{{label_name}}"`

