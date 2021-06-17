---
id: linux.tune2fs
title: Tune2fs
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tune2fs

> Adjust parameters of an ext2, ext3 or ext4 filesystem.
> May be used on mounted filesystems.

- Set the max number of counts before a filesystem is checked to 2:

`tune2fs -c {{2}} {{/dev/sdXN}}`

- Set the filesystem label to MY_LABEL:

`tune2fs -L {{'MY_LABEL'}} {{/dev/sdXN}}`

- Enable discard and user-specified extended attributes for a filesystem:

`tune2fs -o {{discard,user_xattr}} {{/dev/sdXN}}`

- Enable journaling for a filesystem:

`tune2fs -o^{{nobarrier}} {{/dev/sdXN}}`

