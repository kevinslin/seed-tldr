---
id: linux.lsusb
title: Lsusb
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsusb

> Display information about USB buses and devices connected to them.

- List all the USB devices available:

`lsusb`

- List the USB hierarchy as a tree:

`lsusb -t`

- List verbose information about USB devices:

`lsusb --verbose`

- List detailed information about a USB device:

`lsusb -D {{device}}`

- List devices with a specified vendor and product id only:

`lsusb -d {{vendor}}:{{product}}`

