---
id: linux.wine
title: Wine
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wine

> Run Windows programs on Unix.
> More information: <https://wiki.winehq.org/>.

- Run `ipconfig.exe` program:

`wine {{ipconfig}} {{/all}}`

- Run `cmd.exe` in background:

`wine start {{cmd}}`

- Run Windows-like Package Manager:

`wine uninstaller`

- Install MSI packages:

`wine msiexec /i {{package}}`

