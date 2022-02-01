---
id: linux.uvcdynctrl
title: Uvcdynctrl
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uvcdynctrl

> A libwebcam command-line tool to manage dynamic controls in uvcvideo.

- List all available cameras:

`uvcdynctrl -l`

- Specify the device to use (defaults to `video0`):

`uvcdynctrl -d {{device_name}}`

- List available controls:

`uvcdynctrl -c`

- Set a new control value (for negative values, add -- before {{-value}}):

`uvcdynctrl -s {{control_name}} {{value}}`

- Get the current control value:

`uvcdynctrl -g {{control_name}}`

- Save the state of the current controls to a file:

`uvcdynctrl -W {{filename}}`

- Load the state of the controls from a file:

`uvcdynctrl -L {{filename}}`

