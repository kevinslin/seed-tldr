---
id: common.zdb
title: Zdb
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
# zdb

> ZFS debugger.
> More information: <https://manned.org/zdb>.

- Show detailed configuration of all mounted ZFS zpools:

`zdb`

- Show detailed configuration for a specific ZFS pool:

`zdb -C {{poolname}}`

- Show statistics about number, size and deduplication of blocks:

`zdb -b {{poolname}}`

