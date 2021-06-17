---
id: linux.addpart
title: Addpart
desc: ''
updated: 1623965016158
created: 1623965016158
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# addpart

> Tells the Linux kernel about the existence of the specified partition.
> The command is a simple wrapper around the `add partition` ioctl.
> More information: <https://manned.org/addpart>.

- Tell the kernel about the existence of the specified partition:

`addpart {{device}} {{partition}} {{start}} {{length}}`

