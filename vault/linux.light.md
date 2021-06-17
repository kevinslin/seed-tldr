---
id: linux.light
title: Light
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# light

> CLI to control the backlight of your screen.

- Get the current backlight value in percent:

`light`

- Set the backlight value to 50 percent:

`light -S {{50}}`

- Reduce 20 percent from the current backlight value:

`light -U {{20}}`

- Add 20 percent to the current backlight value:

`light -A {{20}}`

