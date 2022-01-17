---
id: linux.qjoypad
title: Qjoypad
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qjoypad

> Translate input from gamepads or joysticks into keyboard strokes or mouse actions.
> More information: <http://qjoypad.sourceforge.net/>.

- Start QJoyPad:

`qjoypad`

- Start QJoyPad and look for devices in a specific directory:

`qjoypad --device={{path/to/directory}}`

- Start QJoyPad but don't show a system tray icon:

`qjoypad --notray`

- Start QJoyPad and force the window manager to use a system tray icon:

`qjoypad --force-tray`

- Force a running instance of QJoyPad to update its list of devices and layouts:

`qjoypad --update`

- Load the given layout in an already running instance of QJoyPad, or start QJoyPad using the given layout:

`qjoypad "{{layout}}"`

