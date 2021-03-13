---
id: windows.choco-feature
title: Choco Feature
desc: ''
updated: 1615663978762
created: 1615663978762
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

