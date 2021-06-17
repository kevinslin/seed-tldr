---
id: common.code
title: Code
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# code

> Visual Studio Code.
> More information: <https://github.com/microsoft/vscode>.

- Open VS Code:

`code`

- Open the current directory in VS Code:

`code .`

- Open a file or directory in VS Code:

`code {{path/to/file_or_directory}}`

- Open a file or directory in the currently open VS Code window:

`code --reuse-window {{path/to/file_or_directory}}`

- Compare two files in VS Code:

`code -d {{file1}} {{file2}}`

- Open VS Code with super user (sudo) permissions:

`sudo code {{path/to/file_or_directory}} --user-data-dir`

