---
id: common.fusermount
title: Fusermount
desc: ''
updated: 1646802118653
created: 1646802118653
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
> More information: <https://manned.org/fusermount>.

- Unmount a FUSE filesystem:

`fusermount -u {{path/to/mount_point}}`

- Unmount a FUSE filesystem as soon as it becomes unused:

`fusermount -z {{path/to/mount_point}}`

- Display version:

`fusermount --version`

