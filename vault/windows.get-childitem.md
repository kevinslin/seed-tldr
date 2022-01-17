---
id: windows.get-childitem
title: Get Childitem
desc: ''
updated: 1642441815127
created: 1642441815127
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Get-ChildItem

> List items in a directory.
> This command can only be used through PowerShell.
> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-childitem>.

- List all non-hidden items in the current directory:

`Get-ChildItem`

- List only directories in the current directory:

`Get-ChildItem -Directory`

- List only files in the current directory:

`Get-ChildItem -File`

- List items in the current directory, including hidden items:

`Get-ChildItem -Hidden`

- List items in a directory other than the current one:

`Get-ChildItem -Path {{path/to/directory}}`

