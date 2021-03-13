---
id: windows.attrib
title: Attrib
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# attrib

> Displays or changes file and directory attributes.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/attrib>.

- Display the attributes of the files in the current directory:

`attrib`

- Display the attributes of the files in the current directory and sub-directories:

`attrib /S`

- Display the attributes of the files and directories in the current directory and sub-directories:

`attrib /S /D`

- Add the read-only attribute to a file:

`attrib +R {{document.txt}}`

- Remove the system and hidden attributes of a file:

`attrib -S -H {{document.txt}}`

- Add the hidden attribute to a directory:

`attrib +H {{path\to\directory}}`

