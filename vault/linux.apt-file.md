---
id: linux.apt-file
title: Apt File
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# apt-file

> Search for files in apt packages, including ones not yet installed.

- Update the metadata database:

`sudo apt update`

- Search for packages that contain the specified file or path:

`apt-file search {{part/of/filename}}`

- List the contents of a specific package:

`apt-file list {{package_name}}`

