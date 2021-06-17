---
id: linux.schroot
title: Schroot
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# schroot

> Run command or start an interactive shell with a different root directory. More customizable than `chroot`.
> More information: <https://wiki.debian.org/Schroot>.

- Run a command in a specific chroot:

`schroot --chroot {{chroot}} {{command}}`

- Run a command with options in a specific chroot:

`schroot --chroot {{chroot}} {{command}} -- {{command_options}}`

- Run a command in all available chroots:

`schroot --all {{command}}`

- Start an interactive shell with in a specific chroot as a specific user:

`schroot --chroot {{chroot}} --user {{user}}`

- List available chroots:

`schroot --list`

