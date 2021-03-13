---
id: linux.winetricks
title: Winetricks
desc: ''
updated: 1615663978758
created: 1615663978758
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

- Specify a custom Wine directory to run winetricks in:

`WINEPREFIX={{path/to/wine_directory}} winetricks`

- Install a Windows DLL or component to the default Wine directory:

`winetricks {{package}}`

