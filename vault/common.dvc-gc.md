---
id: common.dvc-gc
title: Dvc Gc
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
# dvc gc

> Remove unused files and directories from the cache or remote storage.
> More information: <https://dvc.org/doc/command-reference/gc>.

- Garbage collect from the cache, keeping only versions referenced by the current workspace:

`dvc gc --workspace`

- Garbage collect from the cache, keeping only versions referenced by branch, tags, and commits:

`dvc gc --all-branches --all-tags --all-commits`

- Garbage collect from the cache, including the default cloud remote storage (if set):

`dvc gc --all-commits --cloud`

- Garbage collect from the cache, including a specific cloud remote storage:

`dvc gc --all-commits --cloud --remote {{remote_name}}`

