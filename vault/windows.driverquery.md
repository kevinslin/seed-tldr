---
id: windows.driverquery
title: Driverquery
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

