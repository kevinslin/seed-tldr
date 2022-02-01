---
id: windows.get-history
title: Get History
desc: ''
updated: 1642441815128
created: 1642441815128
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Get-History

> Display PowerShell command history.
> This command can only be used through PowerShell.
> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.core/get-history>.

- Display the commands history list with ID:

`Get-History`

- Get PowerShell history item by ID:

`Get-History -Id {{id}}`

- Display the last N commands:

`Get-History -Count {{count}}`

