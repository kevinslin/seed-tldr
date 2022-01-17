---
id: common.colorpicker
title: Colorpicker
desc: ''
updated: 1642441815003
created: 1642441815003
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# colorpicker

> A minimalist X11 colorpicker.
> Any mouse gesture except left click will exit the program.
> More information: <https://github.com/ym1234/colorpicker>.

- Launch colorpicker and print the hexadecimal and RGB value of each clicked pixel to stdout:

`colorpicker`

- Only print the color of one clicked pixel and then exit:

`colorpicker --one-shot`

- Print the color of each clicked pixel and quit when a key is pressed:

`colorpicker --quit-on-keypress`

- Only print the RGB value:

`colorpicker --rgb`

- Only print the hexadecimal value:

`colorpicker --hex`

