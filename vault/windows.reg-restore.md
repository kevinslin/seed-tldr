---
id: windows.reg-restore
title: Reg Restore
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg restore

> Restore a key and its values from a backup file.
> See `reg-save` for more information.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-restore>.

- Overwrite a specified key with data from a backup file:

`reg restore {{key_name}} {{path/to/file}}`

