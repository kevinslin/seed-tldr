---
id: linux.wine
title: Wine
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
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

