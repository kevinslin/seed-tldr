---
id: windows.find
title: Find
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
# find

> Find a specified string in one or more files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/find>.

- Find lines that contain a specified string:

`find {{string}} {{path/to/file_or_directory}}`

- Display lines that do not contain the specified string:

`find {{string}} {{path/to/file_or_directory}} /v`

- Display the count of lines that contain the specified string:

`find {{string}} {{path/to/file_or_directory}} /c`

- Display line numbers with the list of lines:

`find {{string}} {{path/to/file_or_directory}} /n`

