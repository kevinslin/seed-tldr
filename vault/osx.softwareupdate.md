---
id: osx.softwareupdate
title: Softwareupdate
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# softwareupdate

> A tool for updating macOS App Store apps via the command-line.

- List all available updates:

`softwareupdate -l`

- Download and install all updates:

`softwareupdate -ia`

- Download and install all recommended updates:

`softwareupdate -ir`

- Download and install a specific app:

`softwareupdate -i {{update_name}}`

