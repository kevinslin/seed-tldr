---
id: common.xprop
title: Xprop
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xprop

> A tool for displaying window and font properties in an X server.
> More information: <https://manned.org/xprop>.

- Display the name of the root window:

`xprop -root WM_NAME`

- Display the window manager hints for a window:

`xprop -name "{{window_name}}" WM_HINTS`

- Display the point size of a font:

`xprop -font "{{font_name}}" POINT_SIZE`

- Display all the properties of the window with the id 0x200007:

`xprop -id {{0x200007}}`

