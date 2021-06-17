---
id: common.dvc-unfreeze
title: Dvc Unfreeze
desc: ''
updated: 1623965306182
created: 1623965306182
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dvc unfreeze

> Unfreeze stages in the DVC pipeline.
> This allows DVC to start tracking changes in stage dependencies again after they were frozen.
> See also `dvc freeze`.
> More information: <https://dvc.org/doc/command-reference/unfreeze>.

- Unfreeze 1 or more specified stages:

`dvc unfreeze {{stage_name_a}} [{{stage_name_b}} ...]`

