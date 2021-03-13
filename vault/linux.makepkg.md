---
id: linux.makepkg
title: Makepkg
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# makepkg

> Creates a package installable with the `pacman` package manager.
> Runs the commands from a PKGBUILD file to build the package.
> More information: <https://wiki.archlinux.org/index.php/Makepkg>.

- Make a package (run in the same directory as a PKGBUILD):

`makepkg`

- Make a package and install its dependencies:

`makepkg --syncdeps`

- Same as above, but install the package with `pacman` when done:

`makepkg --syncdeps --install`

- Make a package, but skip source checksums:

`makepkg --skipchecksums`

