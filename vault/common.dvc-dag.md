---
id: common.dvc-dag
title: Dvc Dag
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

