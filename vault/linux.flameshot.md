---
id: linux.flameshot
title: Flameshot
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flameshot

> Screenshot utility with a gui interface.
> Supports basic image editing, such as text, shapes, colors, and imgur.
> More information: <https://flameshot.js.org>.

- Launch flameshot in gui mode:

`flameshot launcher`

- Take a screenshot by clicking and dragging:

`flameshot gui`

- Take a full screen screenshot:

`flameshot full`

- Set the save path to write screenshots to:

`flameshot full --path {{path/to/directory}}`

- Delay the screenshot for N milliseconds and output to clipboard:

`flameshot full --delay {{2000}} --clipboard`

