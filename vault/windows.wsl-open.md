---
id: windows.wsl-open
title: Wsl Open
desc: ''
updated: 1642441815130
created: 1642441815130
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wsl-open

> Open a file or URL from within Windows Subsystem for Linux in the user's default Windows GUI application.
> More information: <https://gitlab.com/4U6U57/wsl-open>.

- Open the current directory in Windows Explorer:

`wsl-open {{.}}`

- Open a URL in the user's default web browser in Windows:

`wsl-open {{https://example.com}}`

- Open a specific file in the user's default application in Windows:

`wsl-open {{path/to/file}}`

- Set `wsl-open` as the shell's web browser (open links with `wsl-open`):

`wsl-open -w`

- Display help:

`wsl-open -h`

