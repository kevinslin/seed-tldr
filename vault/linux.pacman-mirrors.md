---
id: linux.pacman-mirrors
title: Pacman Mirrors
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman-mirrors

> Generate a pacman mirrorlist for Manjaro Linux.
> Every run of pacman-mirrors requires you to synchronize your database and update your system using `sudo pacman -Syyu`.
> More information: <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Generate a mirrorlist using the default settings:

`sudo pacman-mirrors --fasttrack`

- Get the status of the current mirrors:

`pacman-mirrors --status`

- Display the current branch:

`pacman-mirrors --get-branch`

- Switch to a different branch:

`sudo pacman-mirrors --api --set-branch {{stable|unstable|testing}}`

- Generate a mirrorlist, only using mirrors in your country:

`sudo pacman-mirrors --geoip`

