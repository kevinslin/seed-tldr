---
id: common.code
title: Code
desc: ''
updated: 1642441815003
created: 1642441815003
stub: false
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

- Open VS Code with superuser (sudo) permissions:

`sudo code {{path/to/file_or_directory}} --user-data-dir`

