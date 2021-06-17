---
id: linux.kpartx
title: Kpartx
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kpartx

> Create device maps from partition tables.

- Add partition mappings:

`kpartx -a {{whole_disk.img}}`

- Delete partition mappings:

`kpartx -d {{whole_disk.img}}`

- List partition mappings:

`kpartx -l {{whole_disk.img}}`

