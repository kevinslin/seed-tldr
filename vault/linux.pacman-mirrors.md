---
id: linux.pacman-mirrors
title: Pacman Mirrors
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

