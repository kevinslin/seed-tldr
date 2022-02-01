---
id: linux.blkid
title: Blkid
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# blkid

> Lists all recognized partitions and their Universally Unique Identifier (UUID).
> More information: <https://manned.org/blkid>.

- List all partitions:

`sudo blkid`

- List all partitions in a table, including current mountpoints:

`sudo blkid -o list`

