---
id: windows.mklink
title: Mklink
desc: ''
updated: 1615663978763
created: 1615663978763
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mklink

> Create symbolic links.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/mklink>.

- Create a symbolic link to a file:

`mklink {{path/to/link}} {{path/to/source_file}}`

- Create a symbolic link to a directory:

`mklink /d {{path/to/link}} {{path/to/source_directory}}`

- Create a hard link to a file:

`mklink /h {{path/to/link}} {{path/to/source_file}}`

- Create a directory junction:

`mklink /j {{path/to/link}} {{path/to/source_file}}`

