---
id: common.dvc-init
title: Dvc Init
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc init

> Initialize a new local DVC repository.
> More information: <https://dvc.org/doc/command-reference/init>.

- Initialize a new local repository:

`dvc init`

- Initialize DVC without Git:

`dvc init --no-scm`

- Initialize DVC in a subdirectory:

`cd {{path/to/subdir}} && dvc init --sudir`

