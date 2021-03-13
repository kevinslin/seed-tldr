---
id: windows.takeown
title: Takeown
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# takeown

> Take ownership of a file or directory.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/takeown>.

- Take ownership of the specified file:

`takeown /f {{path/to/file}}`

- Take ownership of the specified directory:

`takeown /d {{path/to/directory}}`

- Take ownership of the specified directory and all subdirectories:

`takeown /r /d {{path/to/directory}}`

- Change ownership to the Administrator group instead of the current user:

`takeown /a /f {{path/to/file}}`

