---
id: linux.swapon
title: Swapon
desc: ''
updated: 1623965016169
created: 1623965016169
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swapon

> Enables device or file for swapping.

- Get swap information:

`swapon -s`

- Enable a given swap partition:

`swapon {{/dev/sdb7}}`

- Enable a given swap file:

`swapon {{path/to/file}}`

- Enable all swap areas:

`swapon -a`

- Enable swap by label of a device or file:

`swapon -L {{swap1}}`

