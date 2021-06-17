---
id: linux.pacman-deptest
title: Pacman Deptest
desc: ''
updated: 1623965306227
created: 1623965306227
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman --deptest

> Check each dependency specified and return a list of dependencies that are not currently satisfied on the system.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Print the package names of the dependencies that aren't installed:

`pacman --deptest {{package_name1}} {{package_name2}}`

- Check if the installed package satisfies the given minimum version:

`pacman --deptest "{{bash>=5}}"`

- Check if a later version of a package is installed:

`pacman --deptest "{{bash>5}}"`

- Display help:

`pacman --deptest --help`

