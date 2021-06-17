---
id: common.autojump
title: Autojump
desc: ''
updated: 1623965016113
created: 1623965016113
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# autojump

> Quickly jump among the directories you visit the most.
> Aliases like j or jc are provided for even less typing.
> More information: <https://github.com/wting/autojump>.

- Jump to a directory that contains the given pattern:

`j {{pattern}}`

- Jump to a sub-directory (child) of the current directory that contains the given pattern:

`jc {{pattern}}`

- Open a directory that contains the given pattern in the operating system file manager:

`jo {{pattern}}`

- Remove non-existing directories from the autojump database:

`j --purge`

- Show the entries in the autojump database:

`j -s`

