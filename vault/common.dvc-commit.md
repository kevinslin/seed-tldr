---
id: common.dvc-commit
title: Dvc Commit
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc commit

> Record changes to DVC-tracked files in the project.
> More information: <https://dvc.org/doc/command-reference/commit>.

- Commit changes to all DVC-tracked files and directories:

`dvc commit`

- Commit changes to a specified DVC-tracked target:

`dvc commit {{target}}`

- Recursively commit all DVC-tracked files in a directory:

`dvc commit --recursive {{path/to/directory}}`

