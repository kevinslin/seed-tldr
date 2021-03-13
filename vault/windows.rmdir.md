---
id: windows.rmdir
title: Rmdir
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rmdir

> Remove a directory and its contents.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rmdir>.

- Remove an empty directory:

`rmdir {{path/to/directory}}`

- Remove a directory and its contents recursively:

`rmdir {{path/to/directory}} /s`

- Remove a directory and its contents recursively without prompting:

`rmdir {{path/to/directory}} /s /q`

