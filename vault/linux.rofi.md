---
id: linux.rofi
title: Rofi
desc: ''
updated: 1615655543108
created: 1615655543108
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rofi

> An application launcher and window switcher.
> More information: <https://github.com/davatorium/rofi>.

- Show the list of apps:

`rofi -show drun`

- Show the list of all commands:

`rofi -show run`

- Switch between windows:

`rofi -show window`

- Pipe a list of items to stdin and print the selected item to stdout:

`printf "{{Choice1\nChoice2\nChoice3}}" | rofi -dmenu`

