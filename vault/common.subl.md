---
id: common.subl
title: Subl
desc: ''
updated: 1623965016151
created: 1623965016151
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# subl

> Sublime Text editor.
> More information: <https://www.sublimetext.com>.

- Open the current directory in Sublime Text:

`subl {{.}}`

- Open a file or directory in Sublime Text:

`subl {{path/to/file_or_directory}}`

- Open a file and jump to a specific line number:

`subl {{path/to/file}}:{{line_number}}`

- Open a file or directory in the currently open window:

`subl -a {{path/to/file}}`

- Open a file or directory in a new window:

`subl -n {{path/to/file}}`

