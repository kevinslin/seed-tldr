---
id: common.unlink
title: Unlink
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# unlink

> Remove a link to a file from the filesystem.
> The file contents is lost if the link is the last one to the file.

- Remove the specified file if it is the last link:

`unlink {{path/to/file}}`

