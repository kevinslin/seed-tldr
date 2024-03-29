---
id: windows.powershell
title: Powershell
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
# powershell

> Command-line shell and scripting language designed especially for system administration.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- Start a Windows PowerShell session in a Command Prompt window:

`powershell`

- Load a specific PowerShell console file:

`powershell -PSConsoleFile {{path/to/file}}`

- Start a session with a specified version of PowerShell:

`powershell -Version {{version}}`

- Prevent the shell from exit after running startup commands:

`powershell -NoExit`

- Describe the format of data sent to PowerShell:

`powershell -InputFormat {{Text|XML}}`

- Determine how output from PowerShell is formatted:

`powershell -OutputFormat {{Text|XML}}`

- Display help:

`powershell -Help`

