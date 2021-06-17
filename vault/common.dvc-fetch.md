---
id: common.dvc-fetch
title: Dvc Fetch
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
# dvc fetch

> Download DVC tracked files and directories from a remote repository.
> More information: <https://dvc.org/doc/command-reference/fetch>.

- Fetch the latest changes from the default remote upstream repository (if set):

`dvc fetch`

- Fetch changes from a specific remote upstream repository:

`dvc fetch --remote {{remote_name}}`

- Fetch the latest changes for a specific target/s:

`dvc fetch {{target/s}}`

- Fetch changes for all branch and tags:

`dvc fetch --all-branches --all-tags`

- Fetch changes for all commits:

`dvc fetch --all-commits`

