---
id: linux.pacman-database
title: Pacman Database
desc: ''
updated: 1642441815106
created: 1642441815106
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman --database

> Operate on the Arch Linux package database.
> Modify certain attributes of the installed packages.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

`pacman --database --help`

- Mark a package as implicitly installed:

`sudo pacman --database --asdeps {{package_name}}`

- Mark a package as explicitly installed:

`sudo pacman --database --asexplicit {{package_name}}`

- Check that all the package dependencies are installed:

`pacman --database --check`

- Check the repositories to ensure all specified dependencies are available:

`pacman --database --check --check`

- Display only error messages:

`pacman --database --check --quiet`

