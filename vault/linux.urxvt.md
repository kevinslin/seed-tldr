---
id: linux.urxvt
title: Urxvt
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# urxvt

> Rxvt-unicode.
> A customizable terminal emulator.

- Open a new urxvt window:

`urxvt`

- Run in a specific directory:

`urxvt -cd {{path/to/directory}}`

- Run a command in a new urxvt window:

`urxvt -e {{command}}`

- Run a command and keep the window open:

`urxvt --hold -e {{command}}`

- Run a command within the `sh` shell:

`urxvt -e {{sh}} -c {{command}}`
