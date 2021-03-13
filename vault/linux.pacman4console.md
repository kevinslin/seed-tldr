---
id: linux.pacman4console
title: Pacman4console
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pacman4console

> A text-based console game inspired by the original Pacman.
> More information: <https://github.com/YoctoForBeaglebone/pacman4console>.

- Start a game at Level 1:

`pacman4console`

- Start a game on a certain level (there are nine official levels):

`pacman4console --level={{level_number}}`

- Start the pacman4console level editor, saving to a specified text file:

`pacman4consoleedit {{path/to/level_file}}`

- Play a custom level:

`pacman4console --level={{path/to/level_file}}`

