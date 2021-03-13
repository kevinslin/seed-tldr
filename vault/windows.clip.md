---
id: windows.clip
title: Clip
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# clip

> Copy input content to the Windows clipboard.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/clip>.

- Pipe command line output to the Windows clipboard:

`{{dir}} | clip`

- Copy the contents of a file to the Windows clipboard:

`clip < {{path/to/file.ext}}`

- Copy text with a trailing newline to the Windows clipboard:

`echo {{some text}} | clip`

- Copy text without a trailing newline to the Windows clipboard:

`echo | set /p="some text" | clip`

