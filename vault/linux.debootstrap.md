---
id: linux.debootstrap
title: Debootstrap
desc: ''
updated: 1623965306221
created: 1623965306221
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# debootstrap

> Create a basic Debian system.
> More information: <https://wiki.debian.org/Debootstrap>.

- Create a Debian stable release system inside the `debian-root` directory:

`sudo debootstrap stable {{path/to/debian-root/}} http://deb.debian.org/debian`

- Create an Ubuntu 20.04 system inside the `focal-root` directory with a local mirror:

`sudo debootstrap focal {{path/to/focal-root/}} {{file:///path/to/mirror/}}`

- Switch to a bootstrapped system:

`sudo chroot {{path/to/root}}`

- List available releases:

`ls /usr/share/debootstrap/scripts/`

