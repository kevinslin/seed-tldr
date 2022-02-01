---
id: linux.kpartx
title: Kpartx
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kpartx

> Create device maps from partition tables.
> More information: <https://manned.org/kpartx>.

- Add partition mappings:

`kpartx -a {{whole_disk.img}}`

- Delete partition mappings:

`kpartx -d {{whole_disk.img}}`

- List partition mappings:

`kpartx -l {{whole_disk.img}}`

