---
id: linux.pvdisplay
title: Pvdisplay
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pvdisplay

> Display information about Logical Volume Manager (LVM) physical volumes.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/pvdisplay.8.html>.

- Display information about all physical volumes:

`sudo pvdisplay`

- Display information about the physical volume on drive `/dev/sdXY`:

`sudo pvdisplay {{/dev/sdXY}}`

