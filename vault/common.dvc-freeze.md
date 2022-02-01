---
id: common.dvc-freeze
title: Dvc Freeze
desc: ''
updated: 1642441815012
created: 1642441815012
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dvc freeze

> Freeze stages in the DVC pipeline.
> This prevents DVC from tracking changes in stage dependencies and re-execution until unfreeze.
> See also `dvs unfreeze`.
> More information: <https://dvc.org/doc/command-reference/freeze>.

- Freeze 1 or more specified stages:

`dvc freeze {{stage_name_a}} [{{stage_name_b}} ...]`

