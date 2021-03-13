---
id: linux.wipefs
title: Wipefs
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wipefs

> Wipe filesystem, raid, or partition-table signatures from a device.

- Display signatures for specified device:

`sudo wipefs {{/dev/sdX}}`

- Wipe all available signatures for specified device:

`sudo wipefs --all {{/dev/sdX}}`

- Perform dry run:

`sudo wipefs --all --no-act {{/dev/sdX}}`

- Force wipe, even if the filesystem is mounted:

`sudo wipefs --all --force {{/dev/sdX}}`

