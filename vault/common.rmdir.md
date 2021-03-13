---
id: common.rmdir
title: Rmdir
desc: ''
updated: 1615655543082
created: 1615655543082
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rmdir

> Removes a directory.

- Remove directory, provided it is empty. Use `rm -r` to remove non-empty directories:

`rmdir {{path/to/directory}}`

- Remove the target and its parent directories (useful for nested dirs):

`rmdir -p {{path/to/directory}}`

