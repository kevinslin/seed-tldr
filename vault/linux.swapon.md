---
id: linux.swapon
title: Swapon
desc: ''
updated: 1643128140538
created: 1643128140538
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swapon

> Enables device or file for swapping.
> More information: <https://manned.org/swapon>.

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

