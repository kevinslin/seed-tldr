---
id: linux.swapoff
title: Swapoff
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
# swapoff

> Disables device or file for swapping.

- Disable a given swap partition:

`swapoff {{/dev/sdb7}}`

- Disable a given swap file:

`swapoff {{path/to/file}}`

- Disable all swap areas:

`swapoff -a`

- Disable swap by label of a device or file:

`swapoff -L {{swap1}}`

