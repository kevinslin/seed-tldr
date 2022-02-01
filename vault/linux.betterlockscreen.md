---
id: linux.betterlockscreen
title: Betterlockscreen
desc: ''
updated: 1642441815088
created: 1642441815088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# betterlockscreen

> Simple, minimal lock screen.
> More information: <https://github.com/pavanjadhaw/betterlockscreen>.

- Lock the screen:

`betterlockscreen --lock`

- Change the lock screen background:

`betterlockscreen -u {{path/to/image.png}}`

- Lock the screen, showing some custom text:

`betterlockscreen -l pixel -t "{{custom lock screen text}}"`

- Lock the screen, with a custom monitor off timeout in seconds:

`betterlockscreen --off {{5}} -l`

