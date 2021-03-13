---
id: linux.xterm
title: Xterm
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xterm

> A terminal emulator for the X Window System.

- Open the terminal with a title of `Example`:

`xterm -T {{Example}}`

- Open the terminal in fullscreen mode:

`xterm -fullscreen`

- Open the terminal with a dark blue background and yellow foreground (font color):

`xterm -bg {{darkblue}} -fg {{yellow}}`

- Open the terminal with 100 characters per line and 35 lines, in screen position x=200px, y=20px:

`xterm -geometry {{100}}x{{35}}+{{200}}+{{20}}`

- Open the terminal using a Serif font and a font size equal to 20:

`xterm -fa {{'Serif'}} -fs {{20}}`

