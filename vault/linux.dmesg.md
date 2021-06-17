---
id: linux.dmesg
title: Dmesg
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
# dmesg

> Write the kernel messages to standard output.

- Show kernel messages:

`dmesg`

- Show kernel error messages:

`dmesg --level err`

- Show kernel messages and keep reading new ones, similar to `tail -f` (available in kernels 3.5.0 and newer):

`dmesg -w`

- Show how much physical memory is available on this system:

`dmesg | grep -i memory`

- Show kernel messages 1 page at a time:

`dmesg | less`

- Show kernel messages with a timestamp (available in kernels 3.5.0 and newer):

`dmesg -T`

- Show kernel messages in human-readable form (available in kernels 3.5.0 and newer):

`dmesg -H`

- Colorize output (available in kernels 3.5.0 and newer):

`dmesg -L`

