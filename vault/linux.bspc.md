---
id: linux.bspc
title: Bspc
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bspc

> A tool to control `bspwm`.
> More information: <https://github.com/baskerville/bspwm>.

- Define two virtual desktop:

`bspc monitor --reset-desktops {{1}} {{2}}`

- Focus the given desktop:

`bspc desktop --focus {{number}}`

- Close the windows rooted at the selected node:

`bspc node --close`

- Send the selected node to the given desktop:

`bspc node --to-desktop {{number}}`

- Toggle full screen mode for the selected node:

`bspc node --state ~fullscreen`

