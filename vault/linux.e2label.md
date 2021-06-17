---
id: linux.e2label
title: E2label
desc: ''
updated: 1623965016160
created: 1623965016160
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# e2label

> Change the label on an ext2/ext3/ext4 filesystem.

- Change the volume label on a specific ext partition:

`e2label {{/dev/sda1}} "{{label_name}}"`

