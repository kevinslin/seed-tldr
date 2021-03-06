---
id: linux.pacman
title: Pacman
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
# pacman

> Arch Linux package manager utility.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Synchronize and update all packages:

`pacman --sync --refresh --sysupgrade`

- Install a new package:

`pacman --sync {{package_name}}`

- Remove a package and its dependencies:

`pacman --remove --recursive {{package_name}}`

- Search the package database for a regular expression or keyword:

`pacman --sync --search "{{search_pattern}}"`

- List installed packages and versions:

`pacman --query`

- List only the explicitly installed packages and versions:

`pacman --query --explicit`

- List orphan packages (installed as dependencies but not actually required by any package):

`pacman --query --unrequired --deps --quiet`

- Empty the entire pacman cache:

`pacman --sync --clean --clean`

