---
id: windows.findstr
title: Findstr
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# findstr

> Find specified text within one or more files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/findstr>.

- Find space-separated string(s) in all files:

`findstr "{{query}}" *`

- Find space-separated string(s) in a piped command's output:

`{{dir}} | findstr "{{query}}"`

- Find space-separated string(s) in all files recur[s]ively:

`findstr /s "{{query}}" *`

- Find strings using a case-insensitive search:

`findstr /i "{{query}}" *"`

- Find strings in all files using regular expressions:

`findstr /r "{{expression}}" *`

- Find a literal string (containing spaces) in all text files:

`findstr /c:"{{query}}" *.txt`

- Display the line number before each matching line:

`findstr /n "{{query}}" *`

- Display only the filenames that contain a match:

`findstr /m "{{query}}" *`

