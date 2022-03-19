---
id: common.gacutil
title: Gacutil
desc: ''
updated: 1647709363784
created: 1647709363784
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gacutil

> Global Assembly Cache (CAG) management utility.
> More information: <https://manned.org/gacutil>.

- Install the specified assembly into GAC:

`gacutil -i {{path/to/assembly.dll}}`

- Uninstall the specified assembly from GAC:

`gacutil -i {{assembly_display_name}}`

- Print the content of GAC:

`gacutil -l`

