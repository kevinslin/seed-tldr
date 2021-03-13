---
id: common.realpath
title: Realpath
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# realpath

> Display the resolved absolute path for a file or directory.

- Display the absolute path for a file or directory:

`realpath {{path/to/file_or_directory}}`

- Require all path components to exist:

`realpath --canonicalize-existing {{path/to/file_or_directory}}`

- Resolve ".." components before symlinks:

`realpath --logical {{path/to/file_or_directory}}`

- Disable symlink expansion:

`realpath --no-symlinks {{path/to/file_or_directory}}`

- Suppress error messages:

`realpath --quiet {{path/to/file_or_directory}}`

