---
id: windows.driverquery
title: Driverquery
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
# driverquery

> Display information about installed device drivers.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/driverquery>.

- Display a list of all installed device drivers:

`driverquery`

- Display a list of drivers in the specified format:

`driverquery /fo {{table|list|csv}}`

- Display a list of drivers with a column to indicate if they are signed:

`driverquery /si`

- Exclude the header in the output list:

`driverquery /nh`

- Display a list of drivers for a remote machine:

`driverquery /s {{hostname}} /u {{username}} /p {{password}}`

- Display a list of drivers with verbose information:

`driverquery /v`

- Display detailed usage information:

`driverquery /?`

