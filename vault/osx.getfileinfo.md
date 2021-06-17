---
id: osx.getfileinfo
title: Getfileinfo
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
# GetFileInfo

> Get information about a file in an HFS+ directory.

- Display information about a given file:

`GetFileInfo {{path/to/filename}}`

- Display the date and time a given file was created:

`GetFileInfo -d {{path/to/filename}}`

- Display the date and time a given file was last modified:

`GetFileInfo -m {{path/to/filename}}`

- Display the creator of a given file:

`GetFileInfo -c {{path/to/filename}}`

