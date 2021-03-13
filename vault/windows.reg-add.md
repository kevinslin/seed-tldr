---
id: windows.reg-add
title: Reg Add
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg add

> Add new keys and their values to the registry.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-add>.

- Add a new registry key:

`reg add {{key_name}}`

- Add a new value under a specific key:

`reg add {{key_name}} /v {{value}}`

- Add a new value with specific data:

`reg add {{key_name}} /d {{data}}`

- Add a new value to a key with a specific data type:

`reg add {{key_name}} /t {{type}}`

- Forcefully overwrite the existing registry value without a prompt:

`reg add {{key_name}} /f`

