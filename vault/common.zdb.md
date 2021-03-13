---
id: common.zdb
title: Zdb
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zdb

> ZFS debugger.

- Show detailed configuration of all mounted ZFS zpools:

`zdb`

- Show detailed configuration for a specific ZFS pool:

`zdb -C {{poolname}}`

- Show statistics about number, size and deduplication of blocks:

`zdb -b {{poolname}}`

