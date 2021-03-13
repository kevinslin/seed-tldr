---
id: windows.rpcinfo
title: Rpcinfo
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rpcinfo

> List programs via RPC on remote computers.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rpcinfo>.

- List all programs registered on the local computer:

`rpcinfo`

- List all programs registered on a remote computer:

`rpcinfo /p {{computer_name}}`

- Call a specific program on a remote computer using TCP:

`rpcinfo /t {{computer_name}} {{program_name}}`

- Call a specific program on a remote computer using UDP:

`rpcinfo /u {{computer_name}} {{program_name}}`

