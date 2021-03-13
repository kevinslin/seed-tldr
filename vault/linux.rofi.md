---
id: linux.rofi
title: Rofi
desc: ''
updated: 1615663978754
created: 1615663978754
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

