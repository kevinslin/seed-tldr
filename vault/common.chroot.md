---
id: common.chroot
title: Chroot
desc: ''
updated: 1623965016116
created: 1623965016116
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chroot

> Run command or interactive shell with special root directory.
> More information: <https://www.gnu.org/software/coreutils/chroot>.

- Run command as new root directory:

`chroot {{path/to/new/root}} {{command}}`

- Specify user and group (ID or name) to use:

`chroot --userspec={{user:group}}`

