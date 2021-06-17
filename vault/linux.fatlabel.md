---
id: linux.fatlabel
title: Fatlabel
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fatlabel

> Sets or gets the label of a FAT32 partition.

- Get the label of a FAT32 partition:

`fatlabel {{/dev/sda1}}`

- Set the label of a FAT32 partition:

`fatlabel {{/dev/sdc3}} "{{new_label}}"`

