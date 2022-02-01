---
id: linux.brightnessctl
title: Brightnessctl
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
# brightnessctl

> Utility for reading and controlling device brightness for GNU/Linux operating systems.
> More information: <https://github.com/Hummer12007/brightnessctl>.

- List devices with changeable brightness:

`brightnessctl --list`

- Print the current brightness of the display backlight:

`brightnessctl get`

- Set the brightness of the display backlight to a specified percentage within range:

`brightnessctl set {{50%}}`

- Increase brightness by a specified increment:

`brightnessctl set {{+10%}}`

- Decrease brightness by a specified decrement:

`brightnessctl set {{-10%}}`

