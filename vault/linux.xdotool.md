---
id: linux.xdotool
title: Xdotool
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xdotool

> Command-line automation for X11.

- Retrieve the X-Windows window ID of the running Firefox window(s):

`xdotool search --onlyvisible --name {{firefox}}`

- Click the right mouse button:

`xdotool click {{3}}`

- Get the ID of the currently active window:

`xdotool getactivewindow`

- Focus on the window with ID of 12345:

`xdotool windowfocus --sync {{12345}}`

- Type a message, with a 500ms delay for each letter:

`xdotool type --delay {{500}} "Hello world"`

- Press the enter key:

`xdotool key {{KP_Enter}}`

