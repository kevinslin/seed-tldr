---
id: common.pastel
title: Pastel
desc: ''
updated: 1615663978728
created: 1615663978728
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pastel

> Generate, analyze, convert and manipulate colors.
> More information: <https://github.com/sharkdp/pastel>.

- Convert colors from one format to another. Here from RGB to HSL:

`pastel format {{hsl}} {{ff8000}}`

- Show and analyze colors on the terminal:

`pastel color "{{rgb(255,50,127)}}"`

- Pick a color from somewhere on the screen:

`pastel pick`

- Generate a set of N visually distinct colors:

`pastel distinct {{8}}`

- Get a list of all X11 / CSS color names:

`pastel list`

