---
id: sunos.dmesg
title: Dmesg
desc: ''
updated: 1623965016175
created: 1623965016175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dmesg

> Write the kernel messages to standard output.
> More information: <https://www.unix.com/man-page/sunos/1m/dmesg>.

- Show kernel messages:

`dmesg`

- Show how much physical memory is available on this system:

`dmesg | grep -i memory`

- Show kernel messages 1 page at a time:

`dmesg | less`

