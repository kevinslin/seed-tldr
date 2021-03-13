---
id: common.rm
title: Rm
desc: ''
updated: 1615655543082
created: 1615655543082
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rm

> Remove files or directories.

- Remove files from arbitrary locations:

`rm {{path/to/file}} {{path/to/another/file}}`

- Recursively remove a directory and all its subdirectories:

`rm -r {{path/to/directory}}`

- Forcibly remove a directory, without prompting for confirmation or showing error messages:

`rm -rf {{path/to/directory}}`

- Interactively remove multiple files, with a prompt before every removal:

`rm -i {{file(s)}}`

- Remove files in verbose mode, printing a message for each removed file:

`rm -v {{path/to/directory/*}}`

