---
id: common.dvc-diff
title: Dvc Diff
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc diff

> Show changes in DVC tracked file and directories.
> More information: <https://dvc.org/doc/command-reference/diff>.

- Compare DVC tracked files from different Git commits, tags, and branches w.r.t the current workspace:

`dvc diff {{commit_hash/tag/branch}}`

- Compare the changes in DVC tracked files from 1 Git commit to another:

`dvc diff {{revision_b}} {{revision_a}}`

- Compare DVC tracked files, along with their latest hash:

`dvc diff --show-hash {{commit}}`

- Compare DVC tracked files, displaying the output as JSON:

`dvc diff --show-json --show-hash {{commit}}`

- Compare DVC tracked files, displaying the output as Markdown:

`dvc diff --show-md --show-hash {{commit}}`

