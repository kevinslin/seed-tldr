---
id: linux.resize2fs
title: Resize2fs
desc: ''
updated: 1615663978754
created: 1615663978754
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# resize2fs

> Resize an ext2, ext3 or ext4 filesystem.
> Does not resize the underlying partition, and the filesystem must be unmounted.

- Automatically resize a filesystem:

`resize2fs {{/dev/sdXN}}`

- Resize the filesystem to a size of 40G, displaying a progress bar:

`resize2fs -p {{/dev/sdXN}} {{40G}}`

- Shrink the filesystem to its minimum possible size:

`resize2fs -M {{/dev/sdXN}}`

