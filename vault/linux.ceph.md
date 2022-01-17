---
id: linux.ceph
title: Ceph
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ceph

> A unified storage system.
> More information: <https://ceph.io>.

- Check cluster health status:

`ceph status`

- Check cluster usage stats:

`ceph df`

- Get the statistics for the placement groups in a cluster:

`ceph pg dump --format {{plain}}`

- Create a storage pool:

`ceph osd pool create {{pool_name}} {{page_number}}`

- Delete a storage pool:

`ceph osd pool delete {{pool_name}}`

- Rename a storage pool:

`ceph osd pool rename {{current_name}} {{new_name}}`

- Self-repair pool storage:

`ceph pg repair {{pool_name}}`

