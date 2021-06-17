---
id: osx.fileicon
title: Fileicon
desc: ''
updated: 1623965016173
created: 1623965016173
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fileicon

> A macOS CLI to manage custom file and folder icons.
> More information: <https://github.com/mklement0/fileicon>.

- Set a custom icon for a specific file or directory:

`fileicon set {{path/to/file_or_directory}} {{path/to/icon.png}}`

- Remove a custom icon from a specific file or directory:

`fileicon rm {{path/to/file_or_directory}}`

- Save the custom icon of a file or directory as a `.icns` file into the current directory:

`fileicon get {{path/to/file_or_directory}}`

- Test if a specific file or directory has a custom icon:

`fileicon test {{path/to/file_or_directory}}`

