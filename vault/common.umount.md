---
id: common.umount
title: Umount
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# umount

> Unlink a filesystem from its mount point, making it no longer accessible.
> A filesystem cannot be unmounted when it is busy.
> More information: <https://manned.org/umount.8>.

- Unmount a filesystem, by passing the path to the source it is mounted from:

`umount {{path/to/device_file}}`

- Unmount a filesystem, by passing the path to the target where it is mounted:

`umount {{path/to/mounted_directory}}`

- Unmount all mounted filesystems (except the `proc` filesystem):

`umount -a`

