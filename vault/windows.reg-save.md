---
id: windows.reg-save
title: Reg save
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg save

> Save a registry key, its sub keys and values to a file.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-save>.

- Save a registry key, its sub keys and values to a specific file:

`reg save {{key_name}} {{path/to/file}}`

- Forcefully overwrite an existing file without a prompt:

`reg save {{key_name}} {{path/to/file}} /y`

