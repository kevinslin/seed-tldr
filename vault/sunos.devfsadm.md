---
id: sunos.devfsadm
title: Devfsadm
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# devfsadm

> Administration command for `/dev`. Maintains the `/dev` namespace.

- Scan for new disks:

`devfsadm -c disk`

- Cleanup any dangling /dev links and scan for new device:

`devfsadm -C -v`

- Dry-run - output what would be changed but make no modifications:

`devfsadm -C -v -n`

