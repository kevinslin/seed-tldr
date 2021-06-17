---
id: windows.where
title: Where
desc: ''
updated: 1623965306239
created: 1623965306239
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# where

> Display the location of files that match the search pattern.
> Defaults to current work directory and paths in the PATH environment variable.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/where>.

- Display the location of file pattern:

`where {{file_pattern}}`

- Display the location of file pattern including file size and date:

`where /T {{file_pattern}}`

- Recursively search for file pattern at specified path:

`where /R {{path/to/directory}} {{file_pattern}}`

- Display only the error code for the location of file pattern:

`where /Q {{file_pattern}}`

