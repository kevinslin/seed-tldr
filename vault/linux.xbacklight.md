---
id: linux.xbacklight
title: Xbacklight
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

