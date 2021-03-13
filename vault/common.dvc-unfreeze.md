---
id: common.dvc-unfreeze
title: Dvc Unfreeze
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc unfreeze

> Unfreeze stages in the DVC pipeline.
> This allows DVC to start tracking changes in stage dependencies again after they were frozen.
> See also `dvc freeze`.
> More information: <https://dvc.org/doc/command-reference/unfreeze>.

- Unfreeze 1 or more specified stages:

`dvc unfreeze {{stage_name_a}} [{{stage_name_b}} ...]`

