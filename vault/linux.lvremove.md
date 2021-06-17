---
id: linux.lvremove
title: Lvremove
desc: ''
updated: 1623965016164
created: 1623965016164
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lvremove

> Remove one or more logical volumes.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/lvremove.8.html>.

- Remove a logical volume in a volume group:

`sudo lvremove {{volume_group}}/{{logical_volume}}`

- Remove all logical volumes in a volume group:

`sudo lvremove {{volume_group}}`

