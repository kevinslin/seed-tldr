---
id: linux.pacman
title: Pacman
desc: ''
updated: 1642441815107
created: 1642441815107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman

> Arch Linux package manager utility.
> Some subcommands such as `pacman sync` have their own usage documentation.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Synchronize and update all packages:

`sudo pacman --sync --refresh --sysupgrade`

- Install a new package:

`sudo pacman --sync {{package_name}}`

- Remove a package and its dependencies:

`sudo pacman --remove --recursive {{package_name}}`

- Search the package database for a regular expression or keyword:

`pacman --sync --search "{{search_pattern}}"`

- List installed packages and versions:

`pacman --query`

- List only the explicitly installed packages and versions:

`pacman --query --explicit`

- List orphan packages (installed as dependencies but not actually required by any package):

`pacman --query --unrequired --deps --quiet`

- Empty the entire pacman cache:

`sudo pacman --sync --clean --clean`

