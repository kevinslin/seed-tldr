---
id: linux.protontricks
title: Protontricks
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# protontricks

> A simple wrapper that does Winetricks things for Proton enabled games, requires Winetricks.
> More information: <https://github.com/Matoking/protontricks>.

- Show the protontricks help message:

`protontricks`

- Run the protontricks GUI:

`protontricks --gui`

- Run Winetricks for a specific game:

`protontricks {{appid}} {{winetricks_args}}`

- Run a command within a games installation directory:

`protontricks -c {{command}} {{appid}}`

