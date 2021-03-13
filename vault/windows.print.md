---
id: windows.print
title: Print
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# print

> Print a text file to a printer.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/print>.

- Print a text file to the default printer:

`print {{path/to/file}}`

- Print a text file to a specific printer:

`print /d:{{printer}} {{path/to/file}}`

