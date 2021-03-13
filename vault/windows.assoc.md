---
id: windows.assoc
title: Assoc
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# assoc

> Display or modify file extension associations.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/assoc>.

- Display all associated filetypes:

`assoc`

- Display the associated filetype for a specific extension:

`assoc {{.txt}}`

- Modify the associated filetype for a specific extension:

`assoc {{.txt}}={{txtfile}}`

