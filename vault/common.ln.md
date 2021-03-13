---
id: common.ln
title: Ln
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ln

> Creates links to files and directories.

- Create a symbolic link to a file or directory:

`ln -s {{path/to/file_or_directory}} {{path/to/symlink}}`

- Overwrite an existing symbolic link to point to a different file:

`ln -sf {{path/to/new_file}} {{path/to/symlink}}`

- Create a hard link to a file:

`ln {{path/to/file}} {{path/to/hardlink}}`

