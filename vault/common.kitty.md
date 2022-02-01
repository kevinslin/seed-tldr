---
id: common.kitty
title: Kitty
desc: ''
updated: 1642441815039
created: 1642441815039
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kitty

> A fast, feature-rich, GPU based terminal emulator.
> More information: <https://sw.kovidgoyal.net/kitty/>.

- Open a new terminal:

`kitty`

- Open a terminal with the specified title for the window:

`kitty --title "{{title}}"`

- Start the theme-chooser builtin:

`kitty +kitten themes`

- Display an image in the terminal:

`kitty +kitten icat {{path/to/image}}`

- Copy the contents of stdin to the clipboard:

`echo {{example}} | kitty +kitten clipboard`

