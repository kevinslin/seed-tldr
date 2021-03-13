---
id: windows.mklink
title: Mklink
desc: ''
updated: 1615655543118
created: 1615655543118
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mklink

> Create symbolic links.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/mklink>.

- Create a symbolic link to a file:

`mklink {{path/to/link}} {{path/to/source_file}}`

- Create a symbolic link to a directory:

`mklink /d {{path/to/link}} {{path/to/source_directory}}`

- Create a hard link to a file:

`mklink /h {{path/to/link}} {{path/to/source_file}}`

- Create a directory junction:

`mklink /j {{path/to/link}} {{path/to/source_file}}`

