---
id: windows.comp
title: Comp
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
# comp

> Compare the contents of two files or sets of files.
> Use wildcards (\*) to compare sets of files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/comp>.

- Compare files interactively:

`comp`

- Compare two specified files:

`comp {{path/to/file_1}} {{path/to/file_2}}`

- Compare two sets of files:

`comp {{path/to/directory_1/*}} {{path/to/directory_2/*}}`

- Display differences in decimal format:

`comp /d {{path/to/file_1}} {{path/to/file_2}}`

- Display differences in ASCII format:

`comp /a {{path/to/file_1}} {{path/to/file_2}}`

- Display line numbers for differences:

`comp /l {{path/to/file_1}} {{path/to/file_2}}`

- Compare files case-insensitively:

`comp /c {{path/to/file_1}} {{path/to/file_2}}`

- Compare only the first 5 lines of each file:

`comp /n={{5}} {{path/to/file_1}} {{path/to/file_2}}`

