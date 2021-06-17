---
id: linux.winetricks
title: Winetricks
desc: ''
updated: 1623965016171
created: 1623965016171
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# winetricks

> Manage Wine virtual Windows environments.
> More information: <https://wiki.winehq.org/Winetricks>.

- Start a graphical setup at the default Wine location:

`winetricks`

- Specify a custom Wine directory to run Winetricks in:

`WINEPREFIX={{path/to/wine_directory}} winetricks`

- Install a Windows DLL or component to the default Wine directory:

`winetricks {{package}}`

