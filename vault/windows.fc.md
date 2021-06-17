---
id: windows.fc
title: Fc
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fc

> Compare the differences between two files or sets of files.
> Use wildcards (\*) to compare sets of files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/fc>.

- Compare 2 specified files:

`fc {{path/to/file_1}} {{path/to/file_2}}`

- Perform a case-insensitive comparison:

`fc /c {{path/to/file_1}} {{path/to/file_2}}`

- Compare files as Unicode text:

`fc /u {{path/to/file_1}} {{path/to/file_2}}`

- Compare files as ASCII text:

`fc /l {{path/to/file_1}} {{path/to/file_2}}`

- Compare files as binary:

`fc /b {{path/to/file_1}} {{path/to/file_2}}`

- Disable tab-to-space expansion:

`fc /t {{path/to/file_1}} {{path/to/file_2}}`

- Compress whitespace (tabs and spaces) for comparisons:

`fc /w {{path/to/file_1}} {{path/to/file_2}}`

