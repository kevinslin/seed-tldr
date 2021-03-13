---
id: osx.ditto
title: Ditto
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ditto

> Copy files and directories.

- Overwrite contents of destination directory with contents of source directory:

`ditto {{path/to/source}} {{path/to/destination}}`

- Print a line to the Terminal window for every file that's being copied:

`ditto -V {{path/to/source}} {{path/to/destination}}`

- Copy a given file or directory, while retaining the original file permissions:

`ditto -rsrc {{path/to/source}} {{path/to/destination}}`

