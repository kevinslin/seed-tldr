---
id: common.dvc-dag
title: Dvc Dag
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc dag

> Visualize the pipeline(s) defined in `dvc.yaml`.
> More information: <https://dvc.org/doc/command-reference/dag>.

- Visualize the entire pipeline:

`dvc dag`

- Visualize the pipeline stages up to a specified target stage:

`dvc dag {{target}}`

- Export the pipeline in the dot format:

`dvc dag --dot > {{path/to/pipeline.dot}}`

