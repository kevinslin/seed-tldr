---
id: windows.forfiles
title: Forfiles
desc: ''
updated: 1623965306238
created: 1623965306238
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# forfiles

> Select one or more files to execute a specified command on.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/forfiles>.

- Search for files in the current directory:

`forfiles`

- Search for files in a specific directory:

`forfiles /p {{path/to/directory}}`

- Run the specified command for each file:

`forfiles /c "{{command}}"`

- Search for files using a specific glob mask:

`forfiles /m {{glob_pattern}}`

- Search for files recursively:

`forfiles /s`

- Search for files older than 5 days:

`forfiles /d {{+5}}`

