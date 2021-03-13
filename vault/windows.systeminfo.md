---
id: windows.systeminfo
title: Systeminfo
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# systeminfo

> Display operating system configuration for a local or remote machine.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/systeminfo>.

- Display system configuration for the local machine:

`systeminfo`

- Display system configuration in a specified output format:

`systeminfo /fo {{table|list|csv}}`

- Display system configuration for a remote machine:

`systeminfo /s {{remote_name}} /u {{username}} /p {{password}}`

- Display detailed usage information:

`systeminfo /?`

