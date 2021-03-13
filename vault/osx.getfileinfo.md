---
id: osx.getfileinfo
title: Getfileinfo
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# GetFileInfo

> Get information about a file in an HFS+ directory.

- Display information about a given file:

`GetFileInfo {{path/to/filename}}`

- Display the date and time a given file was created:

`GetFileInfo -d {{path/to/filename}}`

- Display the date and time a given file was last modified:

`GetFileInfo -m {{path/to/filename}}`

- Display the creator of a given file:

`GetFileInfo -c {{path/to/filename}}`

