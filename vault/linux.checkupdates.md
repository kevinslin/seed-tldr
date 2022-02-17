---
id: linux.checkupdates
title: Checkupdates
desc: ''
updated: 1645092395215
created: 1645092395215
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# checkupdates

> Tool to check pending updates in Arch Linux.
> More information: <https://man.archlinux.org/man/checkupdates.8>.

- List pending updates:

`checkupdates`

- List pending updates and download the packages to the pacman cache:

`checkupdates --download`

- List pending updates using a specific pacman database:

`CHECKUPDATES_DB={{path/to/directory}} checkupdates`

- Display help:

`checkupdates --help`

