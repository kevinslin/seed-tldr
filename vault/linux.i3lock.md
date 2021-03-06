---
id: linux.i3lock
title: I3lock
desc: ''
updated: 1623965306223
created: 1623965306223
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

- Lock screen with a simple color background (rrggbb format):

`i3lock -c {{0000ff}}`

- Lock screen to a PNG background:

`i3lock -i {{path/to/picture.png}}`

- Disable the unlock indicator (removes feedback on keypress):

`i3lock -u`

- Display mouse pointer instead of hiding it ('default' for default pointer, 'win' for a MS Windows pointer):

`i3lock -p {{default|win}}`

- Lock screen to a PNG background displayed in multiple monitors, with enabled mouse pointer:

`i3lock -i {{path/to/picture.png}} -p {{default|win}} -t`

