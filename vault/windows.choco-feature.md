---
id: windows.choco-feature
title: Choco Feature
desc: ''
updated: 1623965016176
created: 1623965016176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco feature

> Interact with features with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-feature>.

- Display a list of available features:

`choco feature list`

- Enable a feature:

`choco feature enable --name {{name}}`

- Disable a feature:

`choco feature disable --name {{name}}`

