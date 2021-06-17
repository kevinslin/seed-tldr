---
id: windows.cd
title: CD
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cd

> Displays the name of or changes the current working directory.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cd>.

- Go to a directory in the same drive:

`cd {{path/to/directory}}`

- Display the name of the current directory:

`cd`

- Go up to the parent of the current directory:

`cd ..`

- Go to a directory in a different drive:

`cd {{path/to/directory}} /d`

