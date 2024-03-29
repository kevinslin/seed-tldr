---
id: common.zpool
title: Zpool
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zpool

> Manage ZFS pools.
> More information: <https://manned.org/zpool>.

- Show the configuration and status of all ZFS zpools:

`zpool status`

- Check a ZFS pool for errors (verifies the checksum of EVERY block). Very CPU and disk intensive:

`zpool scrub {{pool_name}}`

- List zpools available for import:

`zpool import`

- Import a zpool:

`zpool import {{pool_name}}`

- Export a zpool (unmount all filesystems):

`zpool export {{pool_name}}`

- Show the history of all pool operations:

`zpool history {{pool_name}}`

- Create a mirrored pool:

`zpool create {{pool_name}} mirror {{disk1}} {{disk2}} mirror {{disk3}} {{disk4}}`

- Add a cache (L2ARC) device to a zpool:

`zpool add {{pool_name}} cache {{cache_disk}}`

