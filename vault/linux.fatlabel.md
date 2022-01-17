---
id: linux.fatlabel
title: Fatlabel
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fatlabel

> Sets or gets the label of a FAT32 partition.
> More information: <https://manned.org/fatlabel>.

- Get the label of a FAT32 partition:

`fatlabel {{/dev/sda1}}`

- Set the label of a FAT32 partition:

`fatlabel {{/dev/sdc3}} "{{new_label}}"`

