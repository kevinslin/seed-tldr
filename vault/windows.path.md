---
id: windows.path
title: Path
desc: ''
updated: 1642441815128
created: 1642441815128
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# path

> Display or set the search path for executable files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/path>.

- Display the current path:

`path`

- Set the path to one or more semicolon-separated directories:

`path {{path/to/directory(s)}}`

- Append a new directory to the original path:

`path {{path/to/directory}};%path%`

- Set command prompt to only search the current directory for executables:

`path ;`

