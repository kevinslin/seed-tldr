---
id: osx.softwareupdate
title: Softwareupdate
desc: ''
updated: 1644840636312
created: 1644840636312
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# softwareupdate

> A tool for updating macOS App Store apps via the command-line.
> More information: <https://ss64.com/osx/softwareupdate.html>.

- List all available updates:

`softwareupdate --list`

- Download and install all updates:

`softwareupdate --install --all`

- Download and install all recommended updates:

`softwareupdate --install --req`

- Download and install a specific app:

`softwareupdate --install {{update_name}}`

