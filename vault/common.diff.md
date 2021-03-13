---
id: common.diff
title: Diff
desc: ''
updated: 1615655543050
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# diff

> Compare files and directories.
> More information: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Compare files (lists changes to turn `old_file` into `new_file`):

`diff {{old_file}} {{new_file}}`

- Compare files, ignoring white spaces:

`diff -w {{old_file}} {{new_file}}`

- Compare files, showing the differences side by side:

`diff -y {{old_file}} {{new_file}}`

- Compare files, showing the differences in unified format (as used by `git diff`):

`diff -u {{old_file}} {{new_file}}`

- Compare directories recursively (shows names for differing files/directories as well as changes made to files):

`diff -r {{old_directory}} {{new_directory}}`

- Compare directories, only showing the names of files that differ:

`diff -rq {{old_directory}} {{new_directory}}`

