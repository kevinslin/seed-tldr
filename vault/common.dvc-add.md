---
id: common.dvc-add
title: Dvc Add
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc add

> Add changed files to the index.
> More information: <https://dvc.org/doc/command-reference/add>.

- Add a single target file to the index:

`dvc add {{path/to/file}}`

- Add a target directory to the index:

`dvc add {{path/to/directory}}`

- Recursively add all the files in a given target directory:

`dvc add --recursive {{path/to/directory}}`

- Add a target file with a custom `.dvc` filename:

`dvc add --file {{custom_name.dvc}} {{path/to/file}}`

