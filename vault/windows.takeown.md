---
id: windows.takeown
title: Takeown
desc: ''
updated: 1642441815129
created: 1642441815129
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# takeown

> Take ownership of a file or directory.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/takeown>.

- Take ownership of the specified file:

`takeown /f {{path/to/file}}`

- Take ownership of the specified directory:

`takeown /d {{path/to/directory}}`

- Take ownership of the specified directory and all subdirectories:

`takeown /r /d {{path/to/directory}}`

- Change ownership to the Administrator group instead of the current user:

`takeown /a /f {{path/to/file}}`

