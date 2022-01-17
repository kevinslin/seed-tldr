---
id: common.qtcreator
title: Qtcreator
desc: ''
updated: 1642441815064
created: 1642441815064
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qtcreator

> Cross-platform IDE for Qt applications.
> More information: <https://doc.qt.io/qtcreator/creator-cli.html>.

- Start Qt Creator:

`qtcreator`

- Start Qt Creator and restore the last session:

`qtcreator -lastsession`

- Start Qt Creator but don't load the specified plugin:

`qtcreator -noload {{plugin}}`

- Start Qt Creator but don't load any plugins:

`qtcreator -noload {{all}}`

- Start Qt Creator in presentation mode with pop-ups for keyboard shortcuts:

`qtcreator -presentationMode`

- Start Qt Creator and show the diff from a specific commit:

`qtcreator -git-show {{commit}}`

