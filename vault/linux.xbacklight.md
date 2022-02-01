---
id: linux.xbacklight
title: Xbacklight
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
# xbacklight

> Utility to adjust backlight brightness using the RandR extension.
> More information: <https://gitlab.freedesktop.org/xorg/app/xbacklight>.

- Get the current screen brightness as a percentage:

`xbacklight`

- Set the screen brightness to 40%:

`xbacklight -set {{40}}`

- Increase current brightness by 25%:

`xbacklight -inc {{25}}`

- Decrease current brightness by 75%:

`xbacklight -dec {{75}}`

- Increase backlight to 100%, over 60 seconds (value given in ms), using 60 steps:

`xbacklight -set {{100}} -time {{60000}} -steps {{60}}`

