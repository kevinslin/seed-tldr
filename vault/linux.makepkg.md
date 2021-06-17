---
id: linux.makepkg
title: Makepkg
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# makepkg

> Creates a package installable with the `pacman` package manager.
> Runs the commands from a `PKGBUILD` file to build the package.
> More information: <https://wiki.archlinux.org/index.php/Makepkg>.

- Make a package (run in the same directory as a `PKGBUILD`):

`makepkg`

- Make a package and install its dependencies:

`makepkg --syncdeps`

- Same as above, but install the package with `pacman` when done:

`makepkg --syncdeps --install`

- Make a package, but skip source checksums:

`makepkg --skipchecksums`

