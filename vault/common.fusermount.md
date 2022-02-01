---
id: common.fusermount
title: Fusermount
desc: ''
updated: 1642441815019
created: 1642441815019
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fusermount

> Mount and unmount FUSE filesystems.
> More information: <https://man.archlinux.org/man/fusermount.1>.

- Unmount a FUSE filesystem:

`fusermount -u {{path/to/mount_point}}`

- Unmount a FUSE filesystem as soon as it becomes unused:

`fusermount -z {{path/to/mount_point}}`

- Display version:

`fusermount --version`

