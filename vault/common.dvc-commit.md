---
id: common.dvc-commit
title: Dvc Commit
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
# dvc commit

> Record changes to DVC-tracked files in the project.
> More information: <https://dvc.org/doc/command-reference/commit>.

- Commit changes to all DVC-tracked files and directories:

`dvc commit`

- Commit changes to a specified DVC-tracked target:

`dvc commit {{target}}`

- Recursively commit all DVC-tracked files in a directory:

`dvc commit --recursive {{path/to/directory}}`

