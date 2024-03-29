---
id: linux.arch-chroot
title: Arch Chroot
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arch-chroot

> Enhanced `chroot` command to help in the Arch Linux installation process.
> More information: <https://man.archlinux.org/man/arch-chroot.8>.

- Start an interactive shell (`bash`, by default) in a new root directory:

`arch-chroot {{path/to/new/root}}`

- Specify the user (other than the current user) to run the shell as:

`arch-chroot -u {{user}} {{path/to/new/root}}`

- Run a custom command (instead of the default `bash`) in the new root directory:

`arch-chroot {{path/to/new/root}} {{command}} {{command_arguments}}`

- Specify the shell, other than the default `bash` (in this case, the `zsh` package should have been installed in the target system):

`arch-chroot {{path/to/new/root}} {{zsh}}`

