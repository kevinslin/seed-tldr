---
id: windows.choco-pin
title: Choco Pin
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco pin

> Pin a package at a specific version with Chocolatey.
> Pinned packages are skipped automatically when upgrading.
> More information: <https://chocolatey.org/docs/commands-pin>.

- Display a list of pinned packages and their versions:

`choco pin list`

- Pin a package at its current version:

`choco pin add --name {{package}}`

- Pin a package at a specific version:

`choco pin add --name {{package}} --version {{version}}`

- Remove a pin for a specific package:

`choco pin remove --name {{package}}`

