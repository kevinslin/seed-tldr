---
id: linux.setxkbmap
title: Setxkbmap
desc: ''
updated: 1615663978755
created: 1615663978755
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# setxkbmap

> Set the keyboard using the X Keyboard Extension.

- Set the keyboard in French AZERTY:

`setxkbmap {{fr}}`

- Set multiple keyboard layouts, their variants and switching option:

`setxkbmap -layout {{us,de}} -variant {{,qwerty}} -option {{'grp:alt_caps_toggle'}}`

- Get help:

`setxkbmap -help`

- List all layouts:

`localectl list-x11-keymap-layouts`

- List variants for the layout:

`localectl list-x11-keymap-variants {{de}}`

- List available switching options:

`localectl list-x11-keymap-options | grep grp:`

