---
id: windows.print
title: Print
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
# print

> Print a text file to a printer.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/print>.

- Print a text file to the default printer:

`print {{path/to/file}}`

- Print a text file to a specific printer:

`print /d:{{printer}} {{path/to/file}}`

