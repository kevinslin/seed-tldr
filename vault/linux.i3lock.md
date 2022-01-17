---
id: linux.i3lock
title: I3lock
desc: ''
updated: 1642441815097
created: 1642441815097
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# i3lock

> Simple screen locker built for the i3 window manager.
> More information: <https://i3wm.org/i3lock>.

- Lock the screen showing a white background:

`i3lock`

- Lock the screen with a simple color background (rrggbb format):

`i3lock --color {{0000ff}}`

- Lock the screen to a PNG background:

`i3lock --image {{path/to/file.png}}`

- Lock the screen and disable the unlock indicator (removes feedback on keypress):

`i3lock --no-unlock-indicator`

- Lock the screen and don't hide the mouse pointer:

`i3lock --pointer {{default}}`

- Lock the screen to a PNG background tiled over all monitors:

`i3lock --image {{path/to/file.png}} --tiling`

- Lock the screen and show the number of failed login attempts:

`i3lock --show-failed-attempts`

