---
id: windows.get-content
title: Get Content
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
# Get-Content

> Get the content of the item at the specified location.
> This command can only be used through PowerShell.
> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-content>.

- Display the content of a file:

`Get-Content -Path {{path/to/file}}`

- Display the first few lines of a file:

`Get-Content -Path {{path/to/file}} -TotalCount {{count}}`

- Display the content of the file and keep reading from it until `Ctrl + C` is pressed:

`Get-Content -Path {{path/to/file}} -Wait`

